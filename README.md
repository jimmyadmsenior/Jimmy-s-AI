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

É importante ressaltar que para utilizar a API do Google Gemini, é necessário obter uma chave de API. Quando obter a chave da API, insira ela no arquivo `script_do_chat.js` na pasta `Script`, especificamente na linha 12:

```javascript
const GOOGLE_API_KEY = "SUA_CHAVE_API";
```
## Tutorial de como obter a chave da API do Google Gemini

```bash
# URL do site oficial
https://ai.google.dev/gemini-api/docs?hl=pt-br
```

![](./Código/Media/Print1.png)

```bash
# Passo a Passo
Clique no botão azul "Gerar uma chave da API Gemini".
```

![](./Código/Media/Print2.png)

```bash
# Passo a Passo 2
Clique no botão azul "Criar chave de API".
```

![](./Código/Media/Print3.png)

```bash
# Passo a Passo 3
Selecione um projeto ou crie um novo, depois clique no botão "Criar uma chave de API em um projeto atual".
```

![](./Código/Media/Print4.png)

```bash
# Passo a Passo 3
E por fim, basta copiar a chave gerada pelo site e inserir no na linha 12 do arquvio "script_do_chat", localizado no diretório "Script".
```

## Explicação das escolhas de Design

### System Grid

Eu utilizei o System Grid nos 3 itens de sugestão da tela inicial, os "suggests_itens", onde usei display grid e grid-template-columns para agrupá-los em 3 e ficarem simétricos em relação aos outros elementos da página

### UI/UX

Utilizei uma hierarquia visual e clara, usei uma paleta de cores pequena (branco, preto e cinza), coloquei um espaçamento adequado entre os elementos da página e usei efeitos visuais, como o hover ao passar o cursor nos "suggests_itens". O conteúdo também está organizado em blocos, botões visíveis (CTA), e a navegação é simples e visível.