# Jimmy's AI

## Um Chatbot feito com API do Google Gemini

### Introdução

Neste projeto, desenvolvi um chatbot chamado **Jimmy's AI**, utilizando a API do Google Gemini e JavaScript Vanilla. O objetivo deste trabalho escolar foi criar uma aplicação de IA que simula conversas naturais, permitindo que os usuários interajam de forma intuitiva e envolvente. Através deste chatbot, busquei explorar os conceitos de inteligência artificial, processamento de linguagem natural e desenvolvimento web.

### Objetivos do Projeto

1. **Criar um chatbot interativo:** Desenvolver um aplicativo que possa responder a perguntas e manter uma conversa com os usuários.
2. **Utilizar a API do Google Gemini:** Integrar a API para adicionar funcionalidades de IA ao chatbot, permitindo respostas em linguagem natural.
3. **Construir uma interface amigável:** Projetar uma interface que seja fácil de usar e responsiva, garantindo uma boa experiência para o usuário.

### Visão Geral do Tutorial

#### 1. Introdução a Apps de Chat com IA

Neste primeiro passo, aprendi sobre a importância dos chatbots e como eles são usados em diversas aplicações, desde atendimento ao cliente até assistentes pessoais. Através da API do Google Gemini, pude criar um aplicativo que simula uma conversa real, respondendo a perguntas e interagindo com os usuários de maneira fluida.

#### 2. Conectando-se à API do Gemini

A conexão com a API do Google Gemini foi um dos passos mais importantes do projeto. Segui as instruções para obter minha própria chave de API e a utilizei para autenticar as requisições feitas pelo chatbot. Isso me permitiu acessar as funcionalidades da API, como geração de respostas e compreensão de perguntas.

#### 3. Implementação Passo a Passo em JavaScript

A implementação foi feita em JavaScript Vanilla, o que me proporcionou um aprendizado profundo sobre a linguagem e suas funcionalidades. Estruturei o código para gerenciar as interações do usuário, enviar requisições à API do Gemini e processar as respostas recebidas. O código foi organizado em diferentes funções, facilitando a manutenção e a compreensão do fluxo do aplicativo.

#### 4. Interface Amigável para o Usuário

Projetei uma interface simples e intuitiva, utilizando HTML e CSS. A interface conta com uma área de chat onde as mensagens são exibidas, além de um campo de entrada para o usuário digitar suas perguntas. A responsividade foi uma prioridade, garantindo que o chatbot funcionasse bem em diferentes dispositivos, como smartphones e desktops.

#### 5. Otimização de Desempenho

Para garantir que o chatbot funcionasse de maneira eficiente, implementei técnicas de otimização, como a minimização de requisições à API e o uso de cache para armazenar respostas frequentes. Isso não só melhorou a velocidade de resposta, mas também proporcionou uma melhor experiência ao usuário.

### Aviso

É importante ressaltar que para utilizar a API do Google Gemini, é necessário obter uma chave de API. No vídeo tutorial que elaborei, mostrei como realizar esse processo e como substituir a chave no arquivo `script.js`, especificamente na linha 12:

```javascript
const GOOGLE_API_KEY = "SUA_CHAVE_API";
