# Assistente_por_voz

# Assistente Virtual com Áudio usando OpenAI

Este projeto é um assistente virtual baseado em áudio, que utiliza a API da OpenAI para reconhecer fala, gerar respostas inteligentes e converter texto em áudio. O assistente é capaz de ouvir, processar e responder ao usuário de forma interativa e contínua.

## Funcionalidades

- **Reconhecimento de Fala**: Capta áudio do microfone e transcreve usando a API de reconhecimento de voz.
- **Resposta Inteligente**: Gera respostas dinâmicas com base no contexto da conversa usando o modelo `gpt-3.5-turbo`.
- **Conversão de Texto para Fala**: Transforma as respostas geradas em áudio para interação mais natural.
- **Interrupção Segura**: Permite encerrar a conversa com `Ctrl+C`.

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/ezopI/Assistente_por_voz.git

2. Instale as dependências:
```pip install -r requirements.txt```

3. Crie um arquivo .env com sua chave de API da OpenAI:

```OPENAI_API_KEY=your-api-key```

4. Execute o assistente:
```python assistente_virtual.py```

5. Dependências
- speech_recognition
- openai
- playsound
- python-dotenv

Certifique-se de que seu microfone esteja funcionando corretamente para usar o reconhecimento de fala.

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Muito obrigado!
