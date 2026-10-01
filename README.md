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

Segue um resumo estruturado da sua experiência com o desenvolvimento do Assistente Financeiro Conversacional, considerando o PRD, o MVP gerado e os problemas encontrados durante os testes.

Resumo da Experiência
✅ O que funcionou bem?
Interface simples e intuitiva

O aplicativo apresentou uma interface limpa, amigável e fácil de entender. O saldo atual ficou em destaque, permitindo que o usuário visualize rapidamente sua situação financeira.

Registro financeiro por linguagem natural

O sistema conseguiu reconhecer comandos simples como:

"Gastei R$ 50 no mercado"
"Recebi R$ 3.500 de salário"

Isso validou a proposta principal do projeto: permitir o controle financeiro sem formulários complexos.

Estrutura alinhada ao PRD

As funcionalidades principais previstas no documento foram criadas:

Chat financeiro
Saldo atualizado
Área de Resumo
Área de Metas
Área de Relatórios
Conceito de Design Universal

A navegação é simples, com poucos elementos na tela, favorecendo usuários iniciantes e pessoas com pouca familiaridade com aplicativos financeiros.

❌ O que não funcionou como o esperado?
Falha na correção de lançamentos

O principal problema encontrado foi a impossibilidade de corrigir registros realizados incorretamente pela IA.

Exemplo:

Se o sistema interpretava um valor errado ou registrava uma movimentação incorreta, não existia uma forma simples de corrigir o lançamento.

Falha ao reiniciar os cálculos

Mesmo quando solicitado pelo usuário, o sistema não conseguiu reiniciar corretamente os cálculos financeiros, mantendo informações inconsistentes no saldo.

Ausência de histórico auditável

Não foi possível visualizar claramente:

Qual foi o último lançamento registrado.
Quais alterações foram realizadas.
A sequência das movimentações financeiras.
Ausência de botão "Desfazer"

O sistema não possuía uma funcionalidade para remover o último lançamento registrado.

Isso gerou um problema de usabilidade, pois pequenos erros exigiam a tentativa de reiniciar todo o processo.

Ausência de botão "Refazer"

Após uma ação de correção, também não existia uma forma de restaurar um lançamento removido por engano.

Falta de edição de lançamentos

Não havia um mecanismo para realizar correções simples, como:

Alterar valor.
Alterar categoria.
Alterar descrição.
Alterar forma de pagamento.
Dependência excessiva da interpretação da IA

Quando a IA interpretava um comando de forma incorreta, o usuário ficava sem ferramentas para corrigir rapidamente o erro.

📚 O que aprendi sobre conversar com IAs?
Quanto mais específico o pedido, melhor o resultado

Percebi que a IA responde melhor quando recebe instruções detalhadas sobre comportamento, regras de negócio e experiência do usuário.

O PRD influencia diretamente a qualidade do produto

Muitas das funcionalidades geradas vieram diretamente do que estava documentado no PRD. Quando um requisito não foi descrito com clareza, a IA não o implementou adequadamente.

É importante prever cenários de erro

Ao criar aplicações com IA, não basta pensar apenas no fluxo ideal. É necessário documentar:

Correção de erros.
Desfazer ações.
Recuperação de dados.
Confirmações antes de exclusões.
IA não substitui validação humana

Embora a IA tenha criado rapidamente uma primeira versão funcional, foi necessário testar o sistema para identificar problemas de usabilidade e confiabilidade.

Vibe Coding é um processo iterativo

O desenvolvimento não termina na primeira geração do aplicativo. O valor está em testar, identificar problemas, ajustar o PRD e gerar novas versões mais completas.

Conclusão

O MVP validou com sucesso a ideia de um Assistente Financeiro Conversacional para controle de finanças pessoais, demonstrando que é possível registrar receitas e despesas por meio de linguagem natural de forma simples. Entretanto, os testes revelaram uma deficiência crítica relacionada à gestão de erros: o usuário não consegue corrigir ou desfazer lançamentos incorretos com facilidade. Como próximo passo, recomenda-se implementar funcionalidades de Desfazer, Refazer, Editar Lançamento, Histórico de Movimentações e Confirmação para exclusão de dados, aumentando a confiabilidade e a experiência do usuário na gestão financeira diária.
