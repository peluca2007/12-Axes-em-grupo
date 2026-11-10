# 12 Axes em grupo

Compara o resultado do [12 Axes](https://12axes.vercel.app) do grupo inteiro de uma vez: todo mundo no mesmo gráfico.

**Site:** https://peluca2007.github.io/12-Axes-em-grupo/

## O que tem

- **Ideologia do grupo:** um título calculado pela média de todo mundo, e um botão que abre essa média no 12 Axes para ver a ideologia, os políticos e os países mais próximos do grupo.
- **Perfis:** cada pessoa com radar próprio, posições mais fortes, quem é mais próximo e quem é mais distante.
- **Onde o grupo briga e onde concorda:** os eixos mais divididos, com quem está de cada lado.
- **Duelo:** duas pessoas eixo por eixo, com botão para a compatibilidade oficial no 12 Axes.
- **Os 12 eixos, radar, proximidade e tabela** com todos os números.

## Como colocar alguém no grupo

1. A pessoa faz o teste no [12 Axes](https://12axes.vercel.app) e copia o link da página de resultado.
2. Edite o [`grupo.json`](grupo.json) aqui no GitHub e adicione uma linha:
   ```json
   { "nome": "Fulano", "link": "https://12axes.vercel.app/results?est=..." }
   ```
3. Para a foto, suba a imagem na pasta [`fotos/`](fotos/) com o nome da pessoa (por exemplo, `fulano.jpg`). Veja [`fotos/LEIA-ME.md`](fotos/LEIA-ME.md).

Sem mexer no repositório também dá: no site, use **Adicionar pessoa** e depois **Copiar link do grupo**. O link já abre com todo mundo.

## Sobre

Ferramenta não oficial e sem ligação com o 12 Axes. Ela só lê os números que já estão nos links de resultado de cada pessoa. A "ideologia do grupo" e a "proximidade" são contas da própria página. Para a compatibilidade e as ideologias oficiais, use os botões que abrem o 12 Axes.
