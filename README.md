# Lista de Compras Dinâmica

Lista de compras interativa em uma única página HTML, sem backend e sem dependências.

## Funcionalidades

- Marcar/desmarcar itens tocando na lista
- Barra de progresso geral e por categoria
- Editor de lista: cole um texto e gere a lista automaticamente
- Lista e itens marcados ficam salvos no navegador (localStorage)

## Formato do editor

```
Categoria:
- Item
- Item com observação (texto entre parênteses)
```

- Linhas terminadas em `:` criam uma categoria
- Linhas começando com `-` são itens
- Texto entre parênteses vira uma observação do item

## Uso

Basta abrir o arquivo [`lista-compras.html`](lista-compras.html) em qualquer navegador.

## Publicar no GitHub Pages

1. Suba este repositório no GitHub
2. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`
3. Acesse a URL gerada pelo GitHub Pages (ex: `https://<usuario>.github.io/<repositorio>/lista-compras.html`)
