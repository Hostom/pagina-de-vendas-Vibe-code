# Página de vendas no Vercel

Projeto estático pronto para publicação no Vercel.

## Arquivos principais

- `index.html`: página principal
- `vercel.json`: configuração simples para deploy
- `pagina-vendas-vibe-code.html`: arquivo original mantido como referência

## Como conectar o Cakto

No final do `index.html`, edite:

```html
const CHECKOUT_LINKS = {
  primary: "https://SEU-LINK-DO-CAKTO-AQUI",
  secondary: ""
};
```

Se quiser usar só o Cakto, preencha `primary` e deixe `secondary` vazio.

## Como subir no Vercel

1. Envie esta pasta para um repositório no GitHub.
2. Importe o repositório no Vercel.
3. Publique como projeto estático, sem build command.

## Teste rápido

Abra `index.html` no navegador ou teste com query string:

```text
index.html?checkout=https://seu-checkout.com
```
