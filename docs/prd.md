# 📄 Product Requirements Document (PRD) - Wallet Friend

## 1. Identificação

- **Autor:** (seu nome completo aqui)
- **Projeto:** Wallet Friend - Controle de Gastos Pessoais

---

## 2. Visão Geral e Objetivo

O **Wallet Friend** é uma aplicação web de controle financeiro pessoal que permite ao usuário registrar, categorizar e acompanhar seus gastos de forma simples e visual.

O diferencial da aplicação está no **dashboard inteligente**: ao invés de apenas listar despesas, o sistema transforma os dados em gráficos e indicadores que ajudam o usuário a entender seus padrões de consumo, identificar os maiores gastos e comparar seus hábitos entre meses diferentes — tudo isso com categorias criadas pelo próprio usuário, tornando a experiência totalmente personalizada.

---

## 3. Atores do Sistema

- **Visitante:** Usuário não autenticado que acessa a página inicial e deseja criar uma conta.
- **Usuário Autenticado:** Usuário com conta criada que acessa o sistema para registrar gastos, gerenciar categorias e visualizar o dashboard financeiro.

---

## 4. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### 👤 Épico 1: Autenticação e Conta

- **US01 - Cadastro:** Como um Visitante, quero preencher um formulário com meus dados (nome, e-mail e senha) para criar minha conta no Wallet Friend.
- **US02 - Login:** Como um Visitante, quero inserir meu e-mail e senha para acessar meu painel de controle financeiro.
- **US03 - Logout:** Como um Usuário Autenticado, quero encerrar minha sessão para sair da aplicação com segurança.

### 💸 Épico 2: Lançar Gasto

- **US04 - Registrar Gasto:** Como um Usuário Autenticado, quero preencher um formulário informando descrição, valor, data, tipo (fixo ou variável) e categoria do gasto, para manter meu histórico financeiro atualizado.
- **US05 - Visualizar Gastos:** Como um Usuário Autenticado, quero visualizar uma lista com todos os meus gastos registrados, para acompanhar minhas despesas.
- **US06 - Filtrar Gastos por Categoria:** Como um Usuário Autenticado, quero filtrar minha lista de gastos por categoria, para encontrar rapidamente despesas de um tipo específico.
- **US07 - Excluir Gasto:** Como um Usuário Autenticado, quero excluir um gasto registrado por engano, para manter meu histórico correto.

### 🏷️ Épico 3: Gerenciar Categorias

- **US08 - Criar Categoria:** Como um Usuário Autenticado, quero criar uma categoria personalizada informando nome, cor e ícone, para classificar meus gastos do meu jeito.
- **US09 - Listar Categorias:** Como um Usuário Autenticado, quero visualizar todas as minhas categorias cadastradas, para saber quais já existem antes de criar uma nova.
- **US10 - Excluir Categoria:** Como um Usuário Autenticado, quero excluir uma categoria que não utilizo mais, para manter minha lista de categorias organizada.

### 📊 Épico 4: Dashboard com Gráficos

- **US11 - Total Gasto no Mês:** Como um Usuário Autenticado, quero ver o valor total que gastei no mês atual em destaque no dashboard, para ter uma visão rápida da minha situação financeira.
- **US12 - Gráfico por Categoria:** Como um Usuário Autenticado, quero visualizar um gráfico com a distribuição dos meus gastos por categoria, para entender onde estou gastando mais.
- **US13 - Comparativo entre Meses:** Como um Usuário Autenticado, quero visualizar um gráfico comparando meus gastos dos últimos meses, para identificar tendências no meu comportamento financeiro.
- **US14 - Maior Gasto do Mês:** Como um Usuário Autenticado, quero ver em destaque qual foi meu maior gasto do mês, para saber qual despesa mais pesou no meu orçamento.