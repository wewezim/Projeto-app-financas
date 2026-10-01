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
Crie uma aplicação web responsiva chamada "Assistente Universal de Organização Financeira".
 
Objetivo:
Desenvolver uma plataforma financeira extremamente simples, acessível e inclusiva, baseada em conversação natural.
 
Público:
Qualquer pessoa, independentemente de escolaridade, idade, profissão, alfabetização financeira ou experiência digital.
 
Princípios de UX:
- Design Universal
- Linguagem simples
- Alto contraste
- Ícones ilustrativos
- Textos curtos
- Mobile First
- Acessibilidade WCAG
- Suporte futuro para voz
 
Funcionalidades:
 
1. Chat Financeiro
- Registrar receitas e despesas por linguagem natural.
- Exemplo: "Gastei R$ 50 no mercado."
- Exemplo: "Recebi R$ 3.500 de salário."
 
2. Classificação Automática
Categorias:
- Alimentação
- Despesas do Lar
- Serviços e Manutenção
- Veículos
- Transporte
- Viagens
- Lazer
- Impostos e Taxas
- Cartão de Crédito
- Assinaturas
- Saúde
- Educação
- Outros
 
3. Controle de Saldo
Calcular:
Saldo Atual = Saldo Inicial + Receitas - Despesas
 
4. Metas Financeiras
Permitir criar, acompanhar e atualizar metas.
 
5. Dashboard
Exibir:
- Saldo atual
- Receitas
- Despesas
- Top categorias
- Evolução mensal
- Metas
 
Estrutura de Dados:
 
Tabela Controle_Geral
- id
- data
- saldo_inicial
- total_receitas
- total_despesas
- saldo_atual
 
Tabela Receitas
- id
- data
- categoria
- descricao
- valor
 
Tabela Despesas
- id
- data
- categoria
- subcategoria
- descricao
- forma_pagamento
- valor
 
Tabela Cartao_Credito
- id
- data_compra
- categoria
- descricao
- parcelas
- valor
 
Tabela Metas
- id
- nome_meta
- valor_objetivo
- valor_atual
- progresso
 
Crie:
- Tela de onboarding
- Tela principal de chat
- Dashboard financeiro
- Relatórios
- Metas financeiras
- Visual moderno, amigável e acessível
 
Priorize simplicidade, inclusão, clareza visual e facilidade de uso para usuários iniciantes.
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
