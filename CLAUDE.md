# CLAUDE.md

Jogo de plataforma em HTML puro (canvas) "Animais em Extinção", inspirado em Mario. Projeto de alunos, orientado pelo professor Adilson. O Guarda Florestal precisa resgatar uma Arara capturada por caçadores e derrotar o chefe final.

## Regras do projeto

- Tudo fica em um único `index.html` (HTML, CSS e JavaScript). Sem frameworks, sem build, sem dependências, sem imagens externas: tudo é desenhado no canvas.
- Idioma da interface e dos comentários: português do Brasil.
- O jogo é publicado no GitHub Pages a partir da branch `main`, pasta raiz.
- Controles: A esquerda, D direita, W pular, ESPAÇO atacar.
- Fluxo do jogo: menu, cena de abertura, fase com dois caçadores e o chefe, vitória ao derrotar o chefe e chegar ao fim da fase (`player.x > 2200`).

## Cuidados ao alterar

- Mantenha o código simples e legível: os alunos precisam conseguir ler e editar.
- O código atual é dos alunos: faça mudanças pequenas e explique cada uma.
- Se mudar a vida inicial do Guarda (`player.life`), atualize também o valor `20` da barra de vida na função `draw`.
- Teste abrindo o `index.html` no navegador antes de enviar.
