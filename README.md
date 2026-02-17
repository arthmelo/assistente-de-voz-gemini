# Assistente de Voz com Google Gemini

Assistente de voz inteligente desenvolvido em Python, integrado à API do Google Gemini para processamento de linguagem natural e síntese de voz.

## Sobre 

Esse projeto foi desenvollvido como um desafio de projeto do Bootcamp de GenAI & Dados da plataforma de ensino DIO.Este projeto utiliza um sistema de gravação de áudio baseado na implementação [Gist de Korakot Chaovavanich](https://gist.github.com/korakot/c21c3476c024ad6d56d5f48b0bca92be), que permite a captura de áudio via JavaScript diretamente no ambiente Google Colab e o processamento posterior em Python. 

O fluxo de funcionamento consiste em:

Captura: Gravação de áudio via interface do navegador.
Transcrição: Uso do modelo Whisper para converter fala em texto.
Processamento: Envio do texto para o Google Gemini para gerar uma resposta.
Síntese: Conversão da resposta em áudio via gTTS (Google Text-to-Speech).

## Funcionalidades

- Reconhecimento de fala em tempo real no ambiente Colab.
- Processamento contextual via Google Gemini API.
- Transcrição de áudio robusta com OpenAI Whisper.
- Resposta por voz (Text-to-Speech).
- Suporte a múltiplos idiomas

## Tecnologias e Bibliotecas
O projeto utiliza as seguintes dependências principais:

IA & Processamento:

google-genai: Integração com o modelo Gemini.
openai-whisper: Transcrição de áudio de alta precisão.

Áudio & Interface:

gTTS: Conversão de texto para fala.
IPython.display & google.colab: Manipulação de interface e saída de áudio no notebook.

Utilitários:

os, base64: Manipulação de arquivos e codificação de dados.
