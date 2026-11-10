# Social Media Website

Interface de rede social em **HTML e CSS puros** — sem framework, sem build, sem back-end.

## Origem

Projeto de estudo: reconstrução da interface apresentada no tutorial do canal [EGATOR](https://www.youtube.com/watch?v=AiFfDjmd0jU), feita para praticar layout responsivo com CSS Grid e Flexbox. Não é um produto próprio nem tem funcionalidade real.

## O que está na tela

- Navbar com busca, botão de criar post e avatar.
- Coluna esquerda com perfil, sugestões e atalhos.
- Feed central com stories e cards de postagem.
- Coluna direita com mensagens e pedidos de contato.
- Layout de três colunas que colapsa para uma coluna no mobile.

## Stack

HTML5 · CSS3 (Grid, Flexbox, custom properties) · [Unicons](https://iconscout.com/unicons) para os ícones

## Como abrir

Não tem instalação. Basta abrir o `index.html` no navegador — ou, se preferir servir localmente:

```bash
npx serve .
```

## Limitações

- Sem JavaScript: `index.js` está vazio, nada é dinâmico.
- Sem autenticação, banco de dados ou API — as imagens são estáticas em `images/`.
- Conteúdo (nomes, textos e fotos) é ilustrativo, do material original.
