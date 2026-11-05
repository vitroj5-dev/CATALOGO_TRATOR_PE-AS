# Catálogo Trator Peças — Etapa 2

Abrir `index.html` (hospedar a pasta inteira; as imagens ficam em `assets/`).

## Estrutura
- `index.html` — marcação (cabeçalho, 3 categorias, janelas de produtos e de orçamento).
- `assets/css/catalogo.css` — estilos (identidade amarelo/grafite no final do arquivo).
- `assets/js/catalogo.js` — dados (PRODUTOS, TREE, MANC) e funções (orçamento, WhatsApp, mancal Baldan, pesquisa, navegação).
- `assets/img/` — fotos otimizadas (WebP), carregadas sob demanda.
- `assets/originais/` — as mesmas fotos, sem alteração, como saíam do código antigo.
- `assets/paginas/`, `assets/imagens/` — arquivos que já existiam, mantidos.
- `backup_original/` — cópia integral da versão anterior (index.html de 10,8 MB + assets).

## Como atualizar
- Marcas de Implementos: botões em `#v-implementos` no `index.html` (ordem = ordem da tela).
- Marcas retiradas de Implementos (Jacto, Marcher Brasil, Cadioli) ficam guardadas em `<template id="marcas-fora-de-implementos">`, sem aparecer.
- Produtos de Implementos: lista `IMPL` no fim de `assets/js/catalogo.js` (nome, foto, ficha e modelos `mod`). Peças: `PRODUTOS` e `TREE`.
- Nova foto: salvar em `assets/img/` (WebP ou JPG até ~1800 px) e citar o caminho.
