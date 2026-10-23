# HR FER · Solução em pregos e arames

Site institucional da HR FER, com catálogo de pregos e arames, calibrador de bitolas, calculadora de cerca e cotação direto no WhatsApp.

## Publicação
Hospedado no GitHub Pages (branch `main`, pasta raiz): https://gabrielf021.github.io/site-hfer/

## Como trocar o WhatsApp e o e-mail
No `index.html`, procure por `CONFIG` e altere:

```js
const CONFIG = {
  whatsapp: "5500000000000",        // DDI + DDD + número, só dígitos
  whatsappLabel: "(00) 00000-0000", // como aparece na tela
  email: "contato@hrfer.com.br"
};
```

## Estrutura
- `index.html`: página completa (HTML, CSS e JS em um arquivo)
- `assets/`: logo, símbolo e fotos do manual da marca
