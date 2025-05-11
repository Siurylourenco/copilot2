# Copiloto com Fluxo de Conversa Personalizado - Microsoft Copilot Studio

## Descrição
Este repositório contém um resumo prático sobre como criar um **Copiloto com Fluxo de Conversa Personalizado** no **Microsoft Copilot Studio**. O objetivo do desafio é explorar os conceitos fundamentais da plataforma e configurar um fluxo de conversa dinâmico utilizando **tópicos**, **variáveis**, **entidades**, **respostas generativas** e **ramificações**.

## Componentes Principais no Copilot Studio

### 1. **Tópicos**
Os **tópicos** são a base para a interação com o chatbot, determinando como ele responde às entradas do usuário. A utilização de **tópicos de fallback** é essencial para redirecionar a conversa quando o chatbot não entende a entrada, garantindo que a interação continue sem interrupções.

### 2. **Variáveis**
As **variáveis** armazenam informações durante a conversa, permitindo que o fluxo de interação seja adaptado. Existem dois tipos principais:
- **Variáveis locais**: usadas dentro de um único tópico.
- **Variáveis globais**: acessíveis em todos os tópicos do chatbot.

Elas podem ser de tipos diferentes, como **texto**, **número**, e **data**, e são úteis para personalizar as respostas do chatbot.

### 3. **Entidades**
As **entidades** são usadas para **capturar informações** específicas do usuário, como datas, números de telefone, ou outros dados relevantes para o contexto da conversa. Entidades **personalizadas** podem ser criadas para cenários específicos, enquanto **entidades pré-definidas** já estão disponíveis no sistema.

### 4. **Respostas Generativas**
As **respostas generativas** são respostas dinâmicas criadas automaticamente pela IA com base no contexto da conversa. Para garantir que a IA gere respostas relevantes, é necessário definir um **prompt bem estruturado** e ajustar parâmetros como **temperatura** e **top-p**.

### 5. **Ramificações**
As **ramificações** permitem que o fluxo de conversa siga diferentes caminhos, dependendo das escolhas do usuário. Elas ajudam a personalizar a interação, mas é importante evitar ramificações excessivas para garantir que o fluxo se mantenha simples e fácil de gerenciar.

### 6. **Testando Fluxos**
Testar os fluxos de conversa é crucial para garantir que as respostas do chatbot sejam precisas e que as variáveis, entidades e respostas generativas funcionem corretamente dentro do fluxo.

## Melhoria da Experiência do Usuário
O uso de **respostas generativas** permite que o chatbot forneça respostas mais naturais e contextualmente relevantes, melhorando a experiência do usuário. Elas são particularmente úteis quando o chatbot precisa lidar com **perguntas complexas** ou interações que dependem de informações armazenadas na base de conhecimento.

## Conclusão
Com o **Microsoft Copilot Studio**, é possível criar chatbots inteligentes e dinâmicos, capazes de personalizar interações com os usuários de forma eficaz. A chave para um chatbot bem-sucedido é estruturar os fluxos de conversa de maneira clara e eficiente, usando as ferramentas e recursos oferecidos pela plataforma.

## Link para Repositório GitHub

[Link para o repositório do desafio](#)

## Tecnologias Usadas
- Microsoft Copilot Studio
- Fluxos de Conversa Personalizados
- Variáveis, Entidades e Respostas Generativas

## Licença
Este projeto é de código aberto e está licenciado sob a [Licença MIT](LICENSE).

