# 💸 App de Finanças Pessoais do Weslley Nascimento com Vibe Coding

PRD refinado no Copilot Web:

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
```
Interações com o Lovable:

> crie um app de finanças pessoais com base no seguinte PRD: {PRD}

> infelizmente está havendo um erro no aplicativo. eu digito que entrou um saldo como receita e ele está calculando como despesa, favor verificar o funcionamento do sistema. (Corrigi: o chat não reconhecia como entrada frases como "entrou saldo", "depositei", "caiu um pix", "entrada de R$ 200", "receita" ou "reembolso". Agora elas contam como entrada de dinheiro. Frases com palavras de gasto, como "gastei", "paguei" ou "comprei", continuam contando como saída. Não testei essa mudança no aplicativo. Tente digitar sua frase de novo e veja se o saldo aumenta. Se ainda der errado, me mande a frase exata que você usou.)

> outro problema. eu estou pedindo para ele reiniciar os cálculos, pois ele entendeu errado. e ele não consegue reiniciar. tem de haver um botão ou um entendimento para ele corrigir o lançamento que ele fez. crie, por favor, um botão de desfazer e outro botão de refazer lançamento. (Your work is paused because you're out of credits. 5 free credits arrive in 4 hours.)>

Resultado final no Lovable: https://appcontroleseudinheiro.lovable.app/

<img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/f19ea514-8ff6-48d8-8291-17db78e5f1c5" />

<img width="1144" height="868" alt="image" src="https://github.com/user-attachments/assets/91345c47-c7cc-4f37-906c-e7bad2354b9d" />


Resumo da criação do aplicativo:

<img width="1202" height="2268" alt="image" src="https://github.com/user-attachments/assets/b461765a-522a-475f-ba80-a679a1f166b4" />

## Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como o esperado?
Esperava poder ter uma tecla de erro de lançamento, pois o app não entendia algumas informações simples, como "sobrou dinheiro no caixa" ou "saldo do mês anterior" e acabou raciocinando como se fosse uma despesa, gerando discrepâncias no extrato e no relatório do mês. Se possuísse mais créditos, seria algo a ser aprimorado.

### O que aprendeu sobre conversar com IAs?
Aprendi que a IA possui um método de funcionamento com o qual ela está acostumada a ver em outros sites. No entanto, o prompt bem alimentado por informações úteis faz com que ela gere o resultado final esperado. Assim, deve-se trabalhar com bastante calma e criar um PRD bem elaborado de forma que se consiga atingir o objetivo final.
