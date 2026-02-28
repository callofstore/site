# Call of Store

Projeto unificado com:
- site em `public/`
- bot + API de checkout em `bot-tickets.js`

## Como usar
1. Preencha o `.env` com base no `.env.example`.
2. Rode `npm install`.
3. Rode `npm start`.
4. Abra o site no mesmo domínio/porta do bot.

## Importante
- O checkout do site chama `POST /api/checkout/pix`.
- Depois do pagamento, o cliente envia no Discord: `!comprovante ID_DO_PEDIDO` + anexo.
- Se quiser abrir um servidor específico no botão do site, edite `public/store-config.js`.
