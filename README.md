# StudyAI Universal — Render

1. Envie estes arquivos para um repositório GitHub.
2. No Render: New > Web Service, conecte o repositório.
3. Build Command: `npm install`; Start Command: `npm start`.
4. Em Environment, configure `GEMINI_API_KEY` com sua chave privada e opcionalmente `GEMINI_MODEL`.
5. Faça o deploy. O Render define `PORT` automaticamente.

Não coloque chaves de API no GitHub.

Observação: esta versão mantém o backend Gemini do pacote recuperado; não foi testada com uma chave real.
