# Casos de teste 

### Olá pessoal! 👋🏼

Este repositório foi criado para documentar meu aprendizado sobre casos de teste enquanto estudo para me tornar QA Engineer. Aqui, vou compartilhar um exemplo prático e dicas baseadas no cenário de teste da funcionalidade de login em plataforma web/mobile.

## O que é um Caso de Teste?

Um caso de teste é um conjunto de ações, condições e entradas definidas para verificar se uma funcionalidade de um software está funcionando como esperado. Ele tem como objetivo identificar falhas, garantir a qualidade do produto e validar se os requisitos foram atendidos.

## Principais Pontos de um Caso de Teste

### 1. Título: 

Identifica de forma clara o caso de teste.

### 2. Precondições: 

Condições ou configurações que devem ser atendidas antes do início do teste.

### 3. Passo-a-passo dos testes: 

Lista de etapas para executar o teste.

### 4. Resultado esperado: 

Descrição do que deve ocorrer se o software estiver funcionando corretamente.

### 5. Cenário de teste: 

Contexto geral da funcionalidade a ser avaliada.

### 6. Ambiente de teste: 

Detalhes do ambiente onde o teste foi realizado (sistema operacional, versão do navegador, etc.).

### 7. Status: 

Resultado do teste (“Passou”, “Falhou” ou “Bloqueado”).

### Exemplo fictício: 

<img width="1268" alt="Screenshot 2025-01-17 at 17 05 13" src="https://github.com/user-attachments/assets/a089ea8b-6ebf-4a3c-9b5c-b19c4935e2dd" />

Acima, apresento um exemplo de caso de teste baseado no cenário de login na página. Esse caso é simples, mas abrange pontos fundamentais para garantir o sucesso no aprendizado.

## Benefícios de Criar Casos de Teste

### **Clareza e Documentação:**

Casos de teste bem estruturados são essenciais para documentar claramente o comportamento esperado de um sistema. Isso não só facilita o entendimento de como o sistema deve se comportar em diferentes cenários, mas também serve como uma referência futura para qualquer atualização ou modificação.

### **Prevenção de Erros:**

Criar casos de teste detalhados permite identificar e corrigir falhas e inconsistências de forma antecipada, antes que o produto chegue ao usuário final. Isso reduz significativamente o risco de erros críticos em produção, proporcionando uma maior confiança no lançamento.

### **Reprodução de Bugs:**

Quando um bug é reportado, ter um caso de teste bem definido oferece um guia preciso para reproduzir o problema. Isso acelera o processo de diagnóstico e resolução, permitindo que a equipe de desenvolvimento entenda rapidamente as condições que causaram a falha.

## Exemplo Prático: Casos de Teste para Página de Login

Este exemplo prático descreve uma sequência de cenários de testes para verificar diferentes condições no processo de login de um sistema. Cada cenário foi estruturado com etapas detalhadas e os resultados esperados para validar a funcionalidade do sistema. Abaixo, vou mostrar como esses testes funcionam em alguns cenários:


<img width="1438" alt="Screenshot 2025-01-17 at 19 06 39" src="https://github.com/user-attachments/assets/56d340e1-0670-4126-a9d1-6ad29d192e26" />

Na imagem acima, mostra com mais detalhes alguns cenários de testes como:

1. Faça o login com um e-mail e senha cadastrado
2. Logar com um e-mail não cadastrado
3. Faça o login com um e-mail válido e senha inválido
4. Logar com todos os campos em branco
5. Logar a senha em branco
6. Acessar página de cadastro pelo login

Diante desses cenários que fazemos o Caso de Teste e realizamos os devidos testes. 

No vídeo abaixo, mostro na prática como fazer um teste manual funcional simples conforme as précondições estabelecidas no Caso de Teste. 

https://github.com/user-attachments/assets/21328306-420e-4592-bcd7-fd49bcd13d7c

[Site Serverest](https://front.serverest.dev/login)

[Sheets - Caso de Teste](https://docs.google.com/spreadsheets/d/1bzr7JInLySBT4fA6fuyNoKnfjyiVCkxdTB3ZalQmAyA/edit?usp=sharing)

Este conjunto de testes abrange as situações mais comuns durante o processo de login e garante que o sistema se comporte corretamente em diversos cenários. Além disso, é fundamental registrar o status de cada teste para garantir que a funcionalidade esteja operando conforme o esperado e identificar eventuais falhas que precisam ser corrigidas.


## Dicas para Criar Bons Casos de Teste

### 1. Seja Claro e Objetivo: 

Cada etapa do caso de teste deve ser escrita de forma clara e direta, para que qualquer pessoa que leia o documento possa entender o que está sendo testado e como o teste deve ser executado.

### 2. Divida em Passos Lógicos: 

Estruture os testes de forma sequencial, dividindo-os em etapas simples e fáceis de seguir. Isso não só facilita a execução, mas também torna o teste mais eficiente e menos propenso a erros.

### 3. Descreva Sempre o Resultado Esperado: 

É fundamental especificar claramente o que é considerado "sucesso" para cada etapa do teste. Isso proporciona uma base objetiva para verificar se o comportamento do sistema está correto e alinhado com as expectativas.

### 4. Mantenha Consistência no Formato: 

Adote um formato consistente para todos os casos de teste, com uma estrutura que permita uma leitura fluida e execução sem dificuldades. Isso inclui a utilização de títulos, subtítulos e seções padronizadas, o que facilita a organização e a escalabilidade dos testes ao longo do tempo.

## Considerações Finais

Criar casos de teste eficazes é uma prática essencial para garantir a qualidade do software e evitar surpresas desagradáveis durante a produção. Com uma documentação bem estruturada, conseguimos não apenas prevenir erros, mas também melhorar a comunicação entre as equipes de desenvolvimento, QA e stakeholders.

Lembre-se de que bons casos de teste são claros, objetivos e consistentes, servindo como um guia confiável para qualquer pessoa envolvida no processo. Ao seguir essas boas práticas, você contribui para a construção de produtos mais robustos e de qualidade, além de aprimorar continuamente sua habilidade como um profissional de QA.

Espero que este repositório seja útil para você, especialmente se também está começando a aprender sobre como criar casos de teste de maneira eficiente e eficaz. Se tiver alguma dúvida ou sugestão, não hesite em compartilhar! Vamos aprender e evoluir juntos nesse processo. 🚀👊🏼
