# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.


# PROMPT
"Crie um MVP de um App de Finanças Pessoais chamado 'FinAI'. O foco total é uma interface de chat minimalista e moderna (estilo Mobile-First) onde o usuário registra gastos conversando.
Estilo Visual e UX:
Design: Clean, tons de azul e verde suaves, tipografia moderna.
Navegação: Bottom bar com 3 ícones: 'Chat' (Home), 'Metas' e 'Relatórios'.
Interação: A tela principal deve ser uma interface de chat onde o usuário digita (ex: 'Gastei 50 reais em pizza') e a IA responde confirmando o registro e a categoria.
Funcionalidades Específicas:
Chat Inteligente: Simule uma interface de chat funcional. Use componentes de 'Cards' dentro do chat para mostrar confirmações de gastos e dicas rápidas de economia do 'Agente Financeiro'.
Dashboard de Relatórios: Uma tela com um gráfico simples (Shadcn UI ou Recharts) mostrando os gastos por categoria (Alimentação, Transporte, Lazer).
Metas Financeiras: Uma tela onde o usuário pode criar metas (ex: 'Reserva de Emergência') com uma barra de progresso visual.
Categorização Automática: No fluxo do chat, mostre uma tag automática de categoria após o usuário inserir um dado.
Tecnologia e Tom:
Use React, Tailwind CSS e componentes do Shadcn UI.
Todo o texto deve ser em Português (Brasil).
O tom deve ser educativo, acessível e encorajador para iniciantes.
Apresente primeiro a tela de chat como a experiência central do MVP."



# LOVABLE

<img width="1915" height="906" alt="image" src="https://github.com/user-attachments/assets/28dd67cd-b835-4210-a298-471e6043dd31" />

<img width="1900" height="902" alt="image" src="https://github.com/user-attachments/assets/5e25a777-bbca-4caf-8390-f9377cc1b873" />


# Resumo do Projeto: FinAI
O FinAI é um assistente de finanças pessoais focado em simplicidade. Em vez de planilhas complexas, o usuário organiza sua vida financeira através de conversas naturais. O app permite registrar gastos via chat, categoriza despesas automaticamente, monitora metas de economia e oferece dicas personalizadas através de um Agente Financeiro inteligente.


# Reflexão sobre o Processo
O que funcionou bem?
Velocidade de Prototipagem: A transição da ideia (PRD) para uma interface funcional no Lovable foi extremamente rápida.

Interface Intuitiva: O conceito de "Vibe Coding" permitiu criar um fluxo de chat que parece humano e acolhedor, ideal para o público iniciante.

O que não funcionou como o esperado?
Refinamentos Específicos: Em alguns momentos, a IA interpretou comandos de design de forma genérica, exigindo ajustes manuais e prompts mais detalhados para chegar no visual exato desejado.

Lógica de Dados: A simulação de cálculos complexos em tempo real dentro do protótipo exigiu mais iterações do que a criação visual.


# O que aprendi sobre conversar com IAs?
Contexto é tudo: Aprendi que quanto mais eu descrevo o "sentimento" e o "fluxo" do app, melhor a IA entrega o código.

Iteração Constante: Conversar com a IA não é dar uma ordem única, mas manter um diálogo onde cada resposta dela serve de base para o meu próximo comando (refinamento).

Pensamento Estruturado: Para ser um bom "Vibe Coder", é preciso saber o que quer (o problema) antes de pedir como fazer (a solução).
