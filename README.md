# Miau & Au - Bot de Atendimento a Trocas e Devoluções

Chatbot especialista construído com a API do Google Gemini, especializado em responder
dúvidas sobre a política de troca, devolução, reembolso e garantia de produtos do
petshop fictício Miau & Au.

O bot responde a 3 perguntas do usuário e, ao final, gera um resumo da conversa e a encerra.

## Tecnologias

- Python
- Google Gemini API (google-genai)

## Como executar

1. Clone o repositório

2. Instale as dependências:
   pip install -r requirements.txt

3. Copie o arquivo `.env.example` para `.env` e preencha com sua chave da API do Google:
   GOOGLE_API_KEY=sua_chave_aqui

4. Execute:
   python bot.py

5. Responda às perguntas quando solicitado no terminal
