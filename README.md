# 💸 App de Organização de Finanças Pessoais com Vibe Coding (usuário mayumielipe@gmail.com)

## PRD final retirado do Copilot

```markdown
# PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

## 1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de uma interface conversacional em linguagem natural.
A proposta é substituir formulários e planilhas complexas por uma experiência fluida de diálogo, onde o usuário registra gastos, define metas e recebe recomendações de economia de forma prática.

## 2. Problema
- Usuários desistem de apps financeiros porque exigem muita entrada manual.
- Falta personalização e dicas práticas que motivem o usuário.
- Iniciantes em finanças sentem dificuldade em manter disciplina com ferramentas tradicionais.

## 3. Público-Alvo
- Pessoas que estão começando a organizar suas finanças.
- Usuários que desejam praticidade e simplicidade, sem termos técnicos ou processos burocráticos.
- Faixa etária principal: jovens adultos e adultos que buscam controle básico de gastos.

## 4. Objetivos do Produto
- Permitir registro de gastos de forma natural via chat.
- Automatizar categorização de transações.
- Ajudar usuários a definir e acompanhar metas financeiras simples.
- Oferecer relatórios claros e dicas personalizadas para incentivar economia.
- Criar uma experiência amigável e educativa, sem sobrecarregar o usuário.

## 5. Funcionalidades-Chave (MVP)
1. Chat Financeiro
   - Registrar gastos em linguagem natural.
   - Confirmação automática e categorização sugerida.
2. Metas Financeiras
   - Definição de objetivos simples (ex.: economizar R$200/mês).
   - Barra de progresso visual.
3. Relatórios Básicos
   - Gráfico de pizza com categorias de gastos.
   - Destaques automáticos (“Você gastou mais em alimentação este mês”).
4. Agente Financeiro (Dicas)
   - Recomendações curtas e práticas de economia.
   - Mensagens motivacionais para engajamento.

## 6. Definições das Telas (Estilo Mensageiro)

### Tela 1 – Boas-vindas
- Agente Financeiro: “Olá! Sou seu assistente financeiro. Vamos começar a organizar seus gastos de forma simples. Quer registrar seu primeiro gasto agora?”
- Botões rápidos: [Sim] [Depois]

### Tela 2 – Registro de Gasto
- Usuário: “Gastei R$50 no mercado.”
- Agente Financeiro:
  - “Anotado! Esse gasto foi categorizado como Alimentação.”
  - “Quer que eu adicione à sua meta de economia?”
- Botões rápidos: [Sim] [Não]

### Tela 3 – Metas Financeiras
- Agente Financeiro: “Qual meta você gostaria de definir? Exemplo: economizar R$200 este mês.”
- Usuário: “Quero economizar R$200.”
- Agente Financeiro: “Meta criada! Vou acompanhar seu progresso e avisar quando você estiver perto de alcançá-la.”
- Visual: Barra de progresso simples (ex.: 25% concluído).

### Tela 4 – Relatórios Simples
- Agente Financeiro: “Aqui está um resumo dos seus gastos esta semana.”
- Visual:
  - Gráfico de pizza com categorias (Alimentação, Transporte, Lazer).
  - Destaque: “Você gastou mais em Alimentação.”
- Botões rápidos: [Ver detalhes] [Definir nova meta]

### Tela 5 – Dicas Personalizadas
- Agente Financeiro:
  - “Se cozinhar 2 vezes por semana, pode economizar cerca de R$80.”
  - “Quer que eu te lembre disso toda segunda-feira?”
- Botões rápidos: [Sim] [Não]

### Tela 6 – Engajamento Contínuo
- Notificações estilo chat:
  - “Bom dia! Já registrou seus gastos de ontem?”
  - “Parabéns, você já economizou R$50 este mês.”
```

## Interações com o Lovable

> Crie um app de finanças pessoais de acordo com o PRD abaixo: {PRD}

> Permitir que o usuário possa informar o salário

> Adicionar uma tela inicial de autenticação

## Link para o app
https://fluent-finance-bot.lovable.app/

## Capturas de tela do Lovable

![2](https://github.com/user-attachments/assets/cd5dab78-61b5-4c7c-a7a1-7a1ae164aced)

![3](https://github.com/user-attachments/assets/86faa287-275d-46e2-9e49-cf7245000af7)

![4](https://github.com/user-attachments/assets/ca696452-fa5b-4dc4-9ed1-b91992b03c65)

![5](https://github.com/user-attachments/assets/800b6c0f-a8ee-4488-bd1f-97076e20228e)

![6](https://github.com/user-attachments/assets/e75659b4-8c88-4d72-ac6b-04c9ade2215a)

## Funcionalidades do App de Finanças Pessoais
1. Funciona como um assistente financeiro em formato de conversa.  
2. Permite registrar gastos em linguagem natural, sem formulários ou planilhas.  
3. Classifica automaticamente cada transação em categorias (alimentação, transporte, lazer etc.).  
4. Ajuda o usuário a definir e acompanhar metas financeiras simples (ex.: economizar R$200/mês).  
5. Exibe relatórios básicos e personalizados, como gráficos de gastos por categoria.  
6. Oferece dicas práticas de economia e mensagens motivacionais para engajar o usuário.  
7. Toda a experiência é apresentada em estilo mensageiro, com chat, botões rápidos e notificações.  

## Uma breve reflexão sobre o processo

### O que funcionou bem?
O Copilot refinou o PRD antes de ser submetido ao Lovable, apresentando, inclusive, sugestões para as definições de tela, através da descrição do wireframe. O PRD refinado foi submetido ao Lovable com resultado surpreendente, gerando um app funcional quase completo, com uso de chatbot.
### O que não funcionou como o esperado?  
O Lovable não entendeu de imediato, que o app precisava permitir ao usuário informar o salário, o que exigiu uma iteração adicional, consumindo crédito. Além disso, não foi criado uma tela de autenticação e, ao solicitar que a mesma fosse criada, os créditos acabaram.
### O que aprendeu sobre conversar com IAs?
Através da linguagem natural é possível economizar muito trabalho manual que seria necessário com escrita de código, permitindo ao desenvolvedor focar em pensar sobre o que o app vai fazer e não em como ele vai fazer. Ao utilizar a linguagem natural, quando maior a clareza daquilo que queremos que a IA faça, melhor será o resultado.
