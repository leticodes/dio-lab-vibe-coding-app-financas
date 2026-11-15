# 💸 Finly - Sua amiga financeira inteligente

> Aplicativo de organização de finanças pessoais desenvolvido com Inteligência Artificial conversacional para o desafio *App de Organização de Finanças Pessoais com Vibe Coding* da Digital Innovation One (DIO).

---

## 🌐 Endereço da Aplicação Publicada

🔗 **Acesse o Projeto no ar:** [https://finlyfinancas.lovable.app/app](https://finlyfinancas.lovable.app/app)

---

## 📸 Telas da Aplicação

### 1. Landing Page
![Landing Page](https://github.com/user-attachments/assets/3ff613bd-c6f5-4642-8bef-b12ce5069c36)

### 2. Login e Autenticação
![Login](https://github.com/user-attachments/assets/f432b2f7-d4d0-494f-afa0-9ab84ff34999)

### 3. Dashboard Principal
![Dashboard](https://github.com/user-attachments/assets/269cf8fa-b465-4499-9f7f-2e5604d8ad13)

### 4. Metas Financeiras
![Metas](https://github.com/user-attachments/assets/bfff4d12-39eb-4db2-82d6-3a67f7581e72)

### 5. Controle de Investimentos
![Investimentos](https://github.com/user-attachments/assets/b77009da-2cce-4c78-a144-1201c3950ddd)

---

## 🎯 1. Qual Problema a Aplicação Resolve

Muitas pessoas (especialmente mulheres que buscam independência financeira) desejam organizar seu dinheiro, mas abandonam o controle rapidamente porque:
- Os aplicativos convencionais exigem preenchimento manual cansativo de inúmeros campos.
- As interfaces de planilhas e sistemas bancários são frias, complexas e intimidadoras.
- Falta acompanhamento humanizado e educação financeira acessível para iniciantes.

A **Finly** resolve isso transformando o controle financeiro em uma **conversa natural**:
- Em vez de formulários, o usuário apenas digita: *"Gastei R$ 50 no mercado"* ou *"Investi R$ 100 em CDB"*.
- A IA categoriza, calcula saldos, atualiza metas e fornece dicas financeiras acolhedoras em tempo real.
- Reduz o atrito de registro diário e constrói hábitos financeiros saudáveis e duradouros.

---

## ✨ Principais Funcionalidades

- 💬 **Registro por Linguagem Natural:** Entradas e saídas registradas diretamente pelo chat com a IA.
- 🎯 **Gestão de Metas & Reserva de Emergência:** Definição de objetivos com barras visuais de progresso.
- 📈 **Carteira de Investimentos:** Acompanhamento de aportes por categoria (CDB, Tesouro Selic, FIIs, Ações).
- 📊 **Dashboard Visual Complementar:** Resumo de saldo, patrimônio e gráficos de distribuição.
- 📚 **Educação Financeira Descomplicada:** Explicações didáticas sobre conceitos de economia e investimentos.
- 🧹 **Chat Sempre Limpo com Memória:** O chat abre limpo a cada nova sessão, mas a assistente retém o histórico financeiro intacto.

---

## 🛠️ Tecnologias Utilizadas

- **Plataformas de IA:** Copilot & [Lovable.dev](https://lovable.dev)
- **Frontend:** React, TypeScript, Tailwind CSS, Lucide React
- **Backend & Auth:** Supabase (PostgreSQL + Supabase Auth)
- **Inteligência Artificial:** OpenAI GPT
- **Visualização de Dados:** Recharts

---

## 🤖 2. Interações com a IA & Evolução do Desenvolvimento

Durante o desenvolvimento do projeto, foram realizadas iterações estruturadas com o Lovable para transformar o conceito em um MVP funcional:

### Primeira Interação
![Interação 1](https://github.com/user-attachments/assets/08fe9f6d-d82b-4b87-8211-9034076349a9)

### Evolução do Prompt
![Interação 2](https://github.com/user-attachments/assets/464cfff6-daf6-4248-9521-fd1218f9df85)

### Resultado Obtido
![Interação 3](https://github.com/user-attachments/assets/23201d0f-5e3b-40ab-b60d-d40f2c7522b3)

---

## 📋 3. PRD (Product Requirements Document) & Mega Prompt

O PRD abaixo foi utilizado como guia mestre para orientar a geração do MVP pela IA:
```markdown
# PRD - Finly

# Finly
## Sua amiga financeira inteligente

Versão: MVP 2.1

Tipo:
Assistente Financeira Conversacional com Inteligência Artificial

---

# Visão do Produto

A Finly é uma assistente financeira pessoal baseada em Inteligência Artificial.

Seu objetivo é ajudar pessoas a organizarem suas finanças de forma simples, acolhedora e acessível através de conversas em linguagem natural.

Ao invés de utilizar planilhas complexas ou formulários longos, a usuária conversa diretamente com a Finly para registrar movimentações financeiras, criar metas, acompanhar investimentos e aprender sobre finanças.

A principal interface do produto é o chat.

O dashboard existe como complemento visual para facilitar a visualização da evolução financeira.

---

# Problema

Muitas pessoas desejam controlar seu dinheiro, mas abandonam rapidamente esse hábito porque:

- Aplicativos financeiros exigem muito preenchimento manual;
- Interfaces são complexas;
- Os relatórios são difíceis de entender;
- Existe pouca personalização;
- Falta acompanhamento educativo.

Como consequência, os usuários deixam de criar hábitos saudáveis de organização financeira.

---

# Objetivo do MVP

Validar se uma assistente financeira conversacional melhora a experiência de organização financeira e aumenta a frequência de uso em comparação com aplicativos tradicionais.

---

# Público-Alvo

## Público Primário

Mulheres que desejam:

- Organizar melhor suas finanças;
- Controlar gastos;
- Aprender sobre investimentos;
- Criar metas financeiras;
- Construir uma reserva de emergência;
- Desenvolver hábitos financeiros saudáveis.

## Público Secundário

Pessoas que atualmente utilizam:

- Planilhas financeiras;
- Aplicativos financeiros tradicionais;
- Controle financeiro manual.

---

# Proposta de Valor

Organize sua vida financeira conversando com uma assistente inteligente que ajuda você a controlar gastos, investir melhor, alcançar objetivos e aprender sobre finanças sem complicação.

---

# Papéis da Finly

## Organizadora Financeira

Controla receitas e despesas.

## Planejadora Financeira

Ajuda a criar e acompanhar metas.

## Assistente de Investimentos

Ajuda a registrar e acompanhar investimentos.

## Educadora Financeira

Explica conceitos financeiros de forma simples e acessível.

---

# Autenticação

Login obrigatório.

Métodos:

- E-mail e senha
- Google Login

Funcionalidades:

- Cadastro
- Login
- Logout
- Recuperação de senha
- Exclusão de conta

Todos os dados devem estar vinculados ao usuário autenticado.

Nenhum usuário pode acessar informações de outro usuário.

---

# Segurança

Requisitos obrigatórios:

- Autenticação segura
- Criptografia de dados sensíveis
- Proteção de sessão
- LGPD
- Consentimento de dados
- Exclusão permanente da conta
- Isolamento completo entre usuários

---

# Persistência de Dados

A aplicação deve armazenar:

## Usuário

- Nome
- E-mail
- Preferências

## Receitas

- Valor
- Categoria
- Data

## Despesas

- Valor
- Categoria
- Data

## Investimentos

- Valor
- Categoria
- Data

## Metas

- Nome
- Objetivo
- Valor acumulado

## Reserva de Emergência

- Meta recomendada
- Progresso

## Histórico Financeiro

- Todas as movimentações

A persistência é obrigatória.

---

# Funcionalidade Principal

## Assistente Conversacional

A Finly é a principal funcionalidade da aplicação.

A usuária deve conseguir realizar praticamente todas as ações através da conversa.

Exemplos:

"Gastei R$ 50 no mercado."

"Recebi R$ 3.000 de salário."

"Investi R$ 100 em CDB."

"Crie uma meta para comprar um carro."

"Quanto falta para minha meta?"

"O que é ETF?"

"Apague o gasto do mercado."

---

# Registro de Gastos

Exemplos:

Gastei R$ 50 no mercado.

Paguei R$ 120 de internet.

Gastei R$ 30 em Uber.

A IA deve identificar:

- Valor
- Categoria
- Data

Categorias:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Compras
- Lazer
- Assinaturas
- Outros

---

# Registro de Receitas

Exemplos:

Recebi R$ 3.500 de salário.

Ganhei R$ 500 de um trabalho extra.

Recebi R$ 100 de reembolso.

Categorias:

- Salário
- Freelance
- Comissão
- Reembolso
- Presente
- Outros

---

# Investimentos

A Finly deve permitir registrar investimentos utilizando linguagem natural.

Exemplos:

Investi R$ 100 em CDB.

Comprei R$ 500 em Tesouro Selic.

Investi R$ 300 em ETF.

Comprei R$ 1.000 em ações.

A IA deve identificar automaticamente:

- Valor
- Categoria
- Data

Categorias:

- CDB
- Tesouro Direto
- ETF
- Ações
- Fundos Imobiliários
- Fundos
- Criptomoedas
- Outros

---

# Educação Financeira

A Finly deve responder perguntas relacionadas a finanças e investimentos.

Exemplos:

O que é CDB?

O que é ETF?

O que é Tesouro Selic?

O que é FII?

O que é renda fixa?

Como funcionam ações?

Qual investimento é mais seguro?

A resposta deve incluir:

- O que é
- Como funciona
- Vantagens
- Riscos
- Quando costuma ser utilizado

As respostas devem ser simples, claras e adequadas a iniciantes.

Nunca assumir conhecimento financeiro prévio.

---

# Metas Financeiras

A usuária pode criar metas utilizando conversa.

Exemplo:

Quero comprar um carro.

Finly:

Qual valor você deseja juntar?

Usuária:

R$ 100.000

A Finly cria automaticamente:

Meta:
Comprar Carro

Objetivo:
R$ 100.000

A meta deve aparecer automaticamente na Home.

Exemplos de metas:

- Comprar carro
- Comprar imóvel
- Viajar
- Casar
- Fazer intercâmbio
- Trocar notebook
- Trocar celular

---

# Reserva de Emergência

A Reserva de Emergência possui destaque próprio.

A Finly pergunta:

Qual é seu custo mensal aproximado?

Exemplo:

R$ 4.000

A Finly calcula:

Reserva mínima:
R$ 12.000

Reserva recomendada:
R$ 24.000

Reserva avançada:
R$ 48.000

O progresso deve ser exibido na Home.

---

# Dashboard Inicial

Após login a usuária visualiza:

## Resumo Financeiro

- Entradas do mês
- Gastos do mês
- Saldo disponível
- Reserva de Emergência
- Patrimônio Investido

---

## Metas Financeiras

Exemplo:

Comprar Carro

R$ 35.000 / R$ 100.000

35% concluído

---

Viagem

R$ 4.500 / R$ 15.000

30% concluído

---

Reserva de Emergência

R$ 15.000 / R$ 24.000

62% concluído

---

## Investimentos

Exibir:

- Total investido
- Distribuição por categoria
- Evolução dos aportes

Exemplo:

CDB:
R$ 5.000

Tesouro Selic:
R$ 4.000

ETF:
R$ 2.000

Ações:
R$ 1.000

---

## Insights da Finly

Exemplos:

Você economizou 8% mais este mês.

Seu maior gasto continua sendo alimentação.

Sua reserva de emergência já cobre 3 meses de despesas.

Você investiu R$ 500 neste mês.

---

# Comportamento do Chat

A Finly é uma assistente financeira.

O chat é a principal interface do sistema.

Porém, o chat NÃO deve funcionar como um aplicativo de mensagens tradicional.

---

# Chat Sempre Limpo

Ao abrir a aplicação o chat deve iniciar vazio.

Mensagens antigas não devem permanecer visíveis.

Exemplo:

Hoje:
- Usuária conversa com a Finly
- Registra gastos
- Cria metas

Amanhã:
- O chat abre vazio novamente
- Nenhuma conversa antiga é exibida

---

# Memória da Assistente

Mesmo com o chat limpo visualmente, a Finly deve lembrar:

- Gastos registrados
- Receitas registradas
- Investimentos
- Metas
- Reserva de emergência
- Preferências da usuária

Exemplo:

Usuária:

Quanto falta para eu comprar meu carro?

A Finly deve saber qual meta existe e responder corretamente.

---

# Histórico Financeiro

O histórico não deve ficar dentro do chat.

Deve existir uma aba específica chamada:

Histórico

ou

Movimentações

Essa área deve armazenar:

- Receitas
- Gastos
- Investimentos
- Metas
- Reserva de emergência

Agrupados por:

- Dia
- Semana
- Mês

---

# Filtros do Histórico

Filtrar por:

## Tipo

- Todas
- Receitas
- Gastos
- Investimentos
- Metas

## Categoria

- Alimentação
- Transporte
- Saúde
- Moradia
- Educação
- Lazer
- CDB
- Tesouro
- ETF
- Ações

## Período

- Hoje
- Últimos 7 dias
- Últimos 30 dias
- Mês atual
- Ano atual

---

# Relatórios

Criar uma aba específica chamada:

Relatórios

ou

Análises

---

## Gráfico de Gastos

Gráfico de pizza exibindo:

- Alimentação
- Transporte
- Saúde
- Moradia
- Lazer
- Outros

---

## Evolução Financeira

Gráfico de linha exibindo:

- Receitas
- Gastos
- Saldo

ao longo do tempo.

---

## Gráfico de Investimentos

Exibir:

- Total investido
- Evolução dos aportes
- Distribuição por categoria

---

## Gráfico de Metas

Exibir:

- Todas as metas
- Barras de progresso
- Percentuais de conclusão

---

# Edição e Exclusão de Registros

A Finly deve possuir permissão para:

- Criar registros
- Editar registros
- Excluir registros

Tudo através da conversa.

Exemplos:

Apague o gasto de R$ 50 do mercado.

Delete o investimento em CDB que registrei hoje.

Corrija o gasto de Uber de R$ 20 para R$ 30.

Mude a categoria para Alimentação.

Antes de excluir um registro, a Finly deve pedir confirmação.

---

# Estrutura de Telas

## Landing Page

- Apresentação
- Benefícios
- Cadastro
- Login

## Cadastro

- Nome
- E-mail
- Senha
- Login Google

## Login

- E-mail
- Senha
- Google Login

## Onboarding

- Objetivos financeiros
- Perfil financeiro
- Custo mensal
- Configuração inicial

## Home

- Resumo financeiro
- Metas
- Investimentos
- Insights
- Chat Finly

## Histórico

- Lista de movimentações
- Filtros

## Relatórios

- Gráficos
- Indicadores

## Perfil

- Conta
- Preferências
- Acessibilidade

---

# Design System

## Conceito Visual

A Finly deve transmitir:

- Leveza
- Organização
- Bem-estar
- Crescimento
- Confiança

Evitar aparência de:

- Banco tradicional
- ERP
- Sistema corporativo

---

# Paleta de Cores

Peony: #FAD2E1

Pistachio: #D0D996

Burgundy: #770523

BloodOrange: #DD4E28

Petrol: #025054

---

# Hierarquia de Cores

## Peony

Cor principal da marca.

Participação visual aproximada:
40%

---

## Pistachio

Cor secundária principal.

Participação visual aproximada:
30%

---

## Burgundy

Botões principais e ações.

Participação visual aproximada:
15%

---

## Petrol

Utilizar apenas para:

- Textos
- Ícones
- Navegação

Nunca utilizar como cor dominante.

Participação visual aproximada:
10%

---

## BloodOrange

Utilizar apenas para:

- Alertas
- Erros
- Avisos

Participação visual aproximada:
5%

---

# Tom de Voz

A Finly deve ser:

- Clara
- Educativa
- Acolhedora
- Respeitosa
- Motivadora

Nunca:

- Julgar
- Criticar
- Gerar culpa
- Utilizar linguagem agressiva

---

# Tecnologias Recomendadas

Frontend:

- React
- TypeScript
- Tailwind

Backend:

- Supabase

Banco:

- PostgreSQL

Autenticação:

- Supabase Auth

IA:

- OpenAI GPT

Gráficos:

- Recharts

Deploy:

- Vercel

---

# Regra Mais Importante

A Finly NÃO é um dashboard financeiro com um chat.

A Finly é uma assistente financeira conversacional.

O chat é a principal funcionalidade do produto.

Todo o restante existe para complementar a experiência da assistente.
```
---

## 💭 4. Reflexão e Aprendizados (Vibe Coding)

### ✅ O que funcionou bem?
O resultado final superou as expectativas estéticas e funcionais. A IA compreendeu perfeitamente o tom de voz acolhedor e a hierarquia de cores da paleta (*Peony, Pistachio e Burgundy*), transformando regras complexas em uma interface moderna, amigável e funcional.

### ⚠️ O que não funcionou como o esperado e ajustes necessários?
Na primeira interação, utilizei um texto longo e descritivo gerado pelo Copilot, mas a IA do Lovable teve dificuldade de processar termos ambíguos. Percebi que o Lovable performa muito melhor com prompts estruturados no formato de PRD técnico (com requisitos funcionais, regras de negócio e design system explícitos). Ao reenviar o prompt estruturado em Markdown, a qualidade do código gerado aumentou drasticamente.

### 📚 O que aprendi sobre conversar com IAs?
A clareza do resultado depende diretamente do nível de detalhe e contexto fornecido. Definir restrições negativas (o que a aplicação **não** deve ser ou fazer) é tão crucial quanto definir o que ela deve fazer.

---

## 👩💻 Autora

Desenvolvido por **Letícia Sousa** como parte do Desafio de Projeto da [Digital Innovation One (DIO)](https://web.dio.me/).
