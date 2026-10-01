💸 App de Finanças Pessoais com Vibe Coding

Projeto desenvolvido por Weslley Nascimento utilizando Lovable com apoio do Microsoft Copilot para refinamento do PRD.

🎯 Objetivo

Criar um aplicativo de finanças pessoais com foco em:

Simplicidade
Acessibilidade
Linguagem natural
Controle financeiro para iniciantes

A proposta foi validar a experiência de construção de software utilizando conceitos de Vibe Coding, onde o comportamento da aplicação é definido principalmente através de prompts e refinamento de requisitos.

📋 PRD Refinado no Copilot
```
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
`

O desenvolvimento do aplicativo partiu de um PRD (Product Requirements Document) refinado com o apoio do Copilot.

Visualizar PRD completo
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

💬 Interações com o Lovable
Prompt Inicial
```
crie um app de finanças pessoais com base no seguinte PRD: {PRD}
```

Correção de Interpretação de Receitas
```
infelizmente está havendo um erro no aplicativo. eu digito que entrou um saldo como receita e ele está calculando como despesa, favor verificar o funcionamento do sistema.
```


Resposta do Lovable:
```
Corrigi: o chat não reconhecia como entrada frases como "entrou saldo", "depositei", "caiu um pix", "entrada de R$ 200", "receita" ou "reembolso". Agora elas contam como entrada de dinheiro. Frases com palavras de gasto, como "gastei", "paguei" ou "comprei", continuam contando como saída.
```

Solicitação de Correção de Lançamentos
```
outro problema. eu estou pedindo para ele reiniciar os cálculos, pois ele entendeu errado. e ele não consegue reiniciar. tem de haver um botão ou um entendimento para ele corrigir o lançamento que ele fez. crie, por favor, um botão de desfazer e outro botão de refazer lançamento.
```


Resultado:
```
Your work is paused because you're out of credits. 5 free credits arrive in 4 hours.
```

🚀 Resultado Final

🔗 Aplicação publicada

https://appcontroleseudinheiro.lovable.app/

📸 Tela Principal

<img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/d0972482-1149-44f9-80c6-63afe21b4a3c" />


📸 Navegação do Aplicativo

<img width="1123" height="865" alt="image" src="https://github.com/user-attachments/assets/caf4c8e7-594f-4ca1-842c-25cd78c6d172" />


📝 Resumo da Criação

<img width="474" height="2268" alt="image" src="https://github.com/user-attachments/assets/583692a0-0631-410e-908f-3f1857600d7e" />



🤔 Reflexão
✅ O que funcionou bem?

O refinamento do PRD previamente realizado no Copilot ajudou muito durante o desenvolvimento.

Como os créditos gratuitos do Lovable se esgotaram após apenas três interações, ter um documento bem estruturado foi fundamental para que a ferramenta gerasse uma primeira versão bastante próxima do objetivo desejado.

⚠️ O que não funcionou como o esperado?

Eu esperava conseguir corrigir lançamentos com mais facilidade.

Durante os testes, o aplicativo não compreendia algumas entradas simples, como:

"sobrou dinheiro no caixa"
"saldo do mês anterior"

Essas informações acabavam sendo interpretadas como despesas, gerando inconsistências no saldo e nos relatórios.

Além disso, não foi possível implementar um mecanismo de:

Desfazer lançamento
Refazer lançamento
Reiniciar os cálculos corretamente

Devido à limitação de créditos, essas melhorias não puderam ser refinadas.

📚 O que aprendi sobre conversar com IAs?

Aprendi que a qualidade do resultado está diretamente relacionada à qualidade do contexto fornecido.

A IA tende a seguir padrões já utilizados em aplicações semelhantes, mas um PRD bem elaborado ajuda a direcionar o comportamento da ferramenta para o resultado esperado.

O principal aprendizado foi que investir tempo no refinamento dos requisitos antes da geração do sistema reduz significativamente a quantidade de ajustes posteriores.

Em outras palavras:
```
Quanto melhor o PRD, melhor o resultado produzido pela IA.
```

🧠 Aprendizado sobre Vibe Coding
```
Ideia
  ↓
PRD Refinado
  ↓
Prompt bem estruturado
  ↓
Geração do MVP
  ↓
Testes
  ↓
Identificação de falhas
  ↓
Refinamento do PRD
  ↓
Nova versão
```

Esse projeto demonstrou na prática como a qualidade da especificação influencia diretamente a qualidade do software gerado por IA.
