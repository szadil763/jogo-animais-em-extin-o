# 🦜 Animais em Extinção

Jogo de plataforma inspirado em Mario, criado pelos alunos.

## Como jogar

Abra o link do jogo (GitHub Pages):

https://szadil763.github.io/jogo-animais-em-extin-o/

Ou baixe o projeto e abra o arquivo `index.html` no navegador. Não precisa instalar nada.

## Controles

| Tecla | Ação |
|-------|------|
| A | Esquerda |
| D | Direita |
| W | Pular |
| ESPAÇO | Atacar |

O jogo usa o teclado, então não funciona bem em celular.

## Objetivo

Resgatar a Arara capturada pelos caçadores e derrotar o chefe final.

Um Guarda Florestal protege uma Arara ameaçada de extinção. Os caçadores invadem a floresta e roubam a ave, e o Guarda parte para salvá-la. No caminho ele enfrenta dois caçadores e o chefe. Depois de derrotar o chefe, ele precisa seguir até o fim da fase para resgatar a Arara.

## Estrutura

```
jogo-animais-em-extin-o/
├── index.html    # o jogo inteiro (visual + lógica)
├── README.md
└── CLAUDE.md
```

## Como mudar a dificuldade

No `index.html`, procure as variáveis `player`, `hunters` e `boss`:

- `player.life`: vida do Guarda (começa em 20).
- `player.damage`: dano do ataque do Guarda (6).
- `hunters`: cada caçador tem `life` e `maxLife` (12) e `damage` (3).
- `boss`: o chefe tem `life` e `maxLife` (15) e `damage` (5).

Se mudar a vida inicial do Guarda, troque também o número `20` usado na barra de vida (função `draw`), senão a barra fica errada.

## Publicar no GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Em 1 ou 2 minutos o jogo estará no ar.

## Créditos

Projeto criado pelos alunos com o GitHub Copilot, com orientação do professor Adilson.
