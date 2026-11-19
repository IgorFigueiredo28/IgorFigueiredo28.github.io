# Igor Figueiredo · Portfólio

Analista de Suporte de TI · Infraestrutura · N1/N2 e desenvolvedor full stack.

**Site:** https://igorfigueiredo28.github.io

## O que tem no site

- Experiência (Globals, Goodbom, IBM), formação e idiomas.
- Competências de suporte e infraestrutura.
- Desenvolvimento: stack e os projetos FrogShare, MCP do Microsoft Teams e LaneGG.
- Estudo de caso do FrogShare em https://igorfigueiredo28.github.io/frogshare: arquitetura, decisões medidas e o monitoramento em produção. Ele aparece no menu e numa faixa no card do FrogShare.
- Currículos em PDF, de suporte e de desenvolvedor, em português e inglês (`curriculo-ats/`).

## Como é feito

- HTML, CSS e JavaScript puro, sem build: a página principal (`index.html`) e o estudo de caso (`frogshare.html`), que usam as mesmas escolhas de tema e idioma.
- Endereços sem `.html`: o GitHub Pages serve `frogshare.html` em `/frogshare`, então os links usam esse endereço. Quem chega pelo antigo `/frogshare.html` vê o endereço limpo na barra.
- Tema claro/escuro seguindo o sistema, com botão para trocar.
- Português e inglês: o texto em inglês fica no atributo `data-en` de cada elemento, e o botão PT | EN troca tudo.
- Publicado pelo GitHub Pages a cada push na `main`.
