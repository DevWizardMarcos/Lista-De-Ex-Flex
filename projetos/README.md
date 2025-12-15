# 🏆 Projetos Práticos

Projetos completos para aplicar todos os conceitos aprendidos.

---

## 🎲 Projetos com While e For

### 🎲 Adivinhe o Número
**Descrição:** Jogo em que o usuário deve adivinhar um número escolhido pelo programa.

**Destaques:**
- Número aleatório entre 1 e 50
- Tentativas ilimitadas, com dicas se o número é maior/menor
- Mostra o número de tentativas ao acertar
- **Desafio Extra:** Jogar novamente e mensagens divertidas conforme tentativas

**Conceitos:** `while`, `random`, `input()`, condicionais

---

### 🏧 Caixa Eletrônico com Repetição
**Descrição:** Simula um caixa eletrônico que só aceita valores múltiplos de 10.

**Destaques:**
- Valida o valor do saque
- Calcula quantidade de notas (R$50, R$20, R$10)
- **Desafio Extra:** Permite vários saques sem reiniciar o programa

**Conceitos:** `while`, validação de dados, matemática

---

### 📝 Cadastro Contínuo de Usuários
**Descrição:** Permite cadastrar usuários indefinidamente até o usuário decidir parar.

**Destaques:**
- Guarda nome, idade e e-mail
- Validação de e-mail e idade
- Mostra lista de usuários ao final

**Conceitos:** `while`, listas, validação

---

### 📦 Controle de Estoque Interativo
**Descrição:** Sistema de estoque para adicionar, remover ou consultar produtos continuamente.

**Destaques:**
- Inicia com um dicionário de produtos e quantidades
- Menu interativo em loop

**Conceitos:** `while`, dicionários, menu

---

## 📊 Projetos com Listas e Tuplas

### 🎯 Sistema de Ranking de Jogadores
**Descrição:** Sistema completo de ranking.

**Funcionalidades:**
- Use lista de tuplas (nome, pontuação)
- Ordene por pontuação
- Mostre top 3 usando fatiamento
- Permita adicionar e remover jogadores

**Conceitos:** Listas, tuplas, ordenação, fatiamento

---

### 🎯 Histórico de Navegação
**Descrição:** Simula histórico de sites visitados.

**Funcionalidades:**
- Simule histórico de sites visitados (lista)
- Mostre os 5 últimos (fatiamento)
- Remova duplicatas
- Converta histórico antigo em tupla (imutável)

**Conceitos:** Listas, tuplas, sets, fatiamento

---

### 🎯 Cardápio de Restaurante
**Descrição:** Sistema de cardápio dinâmico.

**Funcionalidades:**
- Pratos disponíveis (lista mutável)
- Informações fixas dos pratos em tuplas (nome, preço, calorias)
- Adicione/remova pratos
- Mostre pratos por faixa de preço (fatiamento)

**Conceitos:** Listas, tuplas, estruturas mistas

---

## 🗂️ Projetos com Dicionários e Sets

### 🎯 Sistema de Lista de Compras Inteligente
**Descrição:** Lista de compras completa.

**Funcionalidades:**
- Adicionar itens
- Remover itens
- Evitar itens repetidos (set)
- Salvar e carregar lista
- Mostrar orçamento total (lista de preços)

**Útil para:** Compras mensais, mercado, estoque pessoal

---

### 🎯 Gerenciador de Tarefas com Prioridades
**Descrição:** Sistema de tarefas completo.

**Funcionalidades:**
- Tarefa → {descrição, prioridade, data, status}
- Mostrar tarefas pendentes
- Ordenar por prioridade
- Marcar como concluída
- Exportar relatório

**Útil para:** Estudos, trabalho, rotina

---

### 🎯 Controle de Estoque Simples
**Descrição:** Sistema de controle de estoque.

**Funcionalidades:**
- produto → (quantidade, preço)
- Alerta quando quantidade < 3
- Valor total do estoque
- Adicionar/retirar itens
- Busca por nome

**Útil para:** Pequenos negócios, artesanato, loja online

---

### 🎯 Agenda de Contatos com Busca Avançada
**Descrição:** Agenda completa de contatos.

**Funcionalidades:**
- nome → dados pessoais (telefone, email, cidade)
- Buscar por parte do nome
- Bloquear contatos em uma black list (set)
- Exportar para arquivo

**Útil para:** Contatos profissionais e pessoais

---

### 🎯 Gerador de Cardápio da Semana
**Descrição:** Planejador de refeições.

**Funcionalidades:**
- Lista de refeições disponíveis
- Set de restrições (sem lactose, sem carne etc.)
- Gerar cardápio aleatório semanal
- Evitar repetir pratos
- Salvar escolhas anteriores

**Útil para:** Dieta, organização pessoal, rotina fitness

---

### 🎯 Sistema de Presença de Alunos
**Descrição:** Controle de presença.

**Funcionalidades:**
- alunos_presentes = set()
- Adicionar presença
- Identificar ausentes (diferença entre sets)
- Exportar boletim de presença
- Calcular taxa de presença

**Útil para:** Cursos, workshops, escolas

---

### 🎯 Gerenciador de Finanças Pessoais
**Descrição:** Controle financeiro completo.

**Funcionalidades:**
- Lista de transações → {valor, categoria, data, tipo}
- Relatório mensal
- Categorias mais gastas
- Gastos recorrentes
- Metas financeiras

**Útil para:** Controle de gastos diário

---

### 🎯 Catálogo de Produtos com Filtros
**Descrição:** Sistema de catálogo.

**Funcionalidades:**
- produto → dados (preço, categoria, estoque)
- Filtrar por categoria
- Mostrar categorias disponíveis (set)
- Adicionar e remover produtos

**Útil para:** Loja online, artesanato, revenda

---

### 🎯 Organizador de Estudos
**Descrição:** Planejador de estudos.

**Funcionalidades:**
- matérias → {conteúdos, tempo de estudo, nível de dificuldade}
- Recomendação do que estudar hoje
- Gráfico de progresso
- Revisão inteligente

**Útil para:** Faculdade, cursos, Enem

---

### 🎯 Sistema de Cadastro de Filmes/Séries
**Descrição:** Catálogo de entretenimento.

**Funcionalidades:**
- filme → {gêneros (set), ano, nota, plataforma}
- Buscar por gênero
- Recomendação de filmes com base no que você já viu
- Evitar filmes duplicados (set)
- Ranking de favoritos

**Útil para:** Netflix, Prime, catálogo pessoal

---

## 🎓 Projetos com Funções e Módulos

### 🎯 Sistema de Calculadora Modular
**Estrutura:**
- `operacoes.py` (funções matemáticas)
- `historico.py` (salvar histórico em JSON)
- `main.py` (interface)

**Funcionalidades:**
- Operações básicas em módulo separado
- Salvar histórico usando json
- Menu interativo

---

### 🎯 Gerador de Senhas
**Módulos:**
- `gerador.py` (funções de geração)
- `validador.py` (verificar força)
- `main.py`

**Bibliotecas:**
- random (caracteres aleatórios)
- string (letras e símbolos)
- re (validação com regex)

---

### 🎯 Sistema de Tarefas com Arquivo
**Estrutura:**
- `tarefas.py` (CRUD de tarefas)
- `arquivo.py` (salvar/carregar JSON)
- `utils.py` (formatação de datas)
- `main.py`

**Bibliotecas:**
- json
- datetime
- os

---

### 🎯 Análise de Texto
**Funcionalidades:**
- Contar palavras, letras, frases
- Palavras mais frequentes
- Estatísticas completas

**Bibliotecas:**
- re (limpeza de texto)
- collections.Counter
- string

---

### 🎯 Consulta de CEP
**Funcionalidades:**
- Buscar CEP na API ViaCEP
- Salvar consultas em JSON
- Histórico de buscas

**Bibliotecas:**
- requests (API)
- json (salvar dados)
- datetime (timestamp)

---

### 🎯 Jogo de Adivinhação Modular
**Estrutura:**
- `jogo.py` (lógica do jogo)
- `placar.py` (ranking de jogadores)
- `config.py` (configurações)
- `main.py`

**Bibliotecas:**
- random
- json (salvar ranking)
- time (temporizador)

---

## 💡 Dicas para Projetos

### Antes de Começar:
- Planeje a estrutura do projeto
- Liste as funcionalidades principais
- Identifique quais conceitos você vai usar
- Crie um esboço da interface (se houver)

### Durante o Desenvolvimento:
- Divida em etapas pequenas
- Teste cada funcionalidade isoladamente
- Comente seu código
- Use nomes descritivos para variáveis e funções

### Ao Finalizar:
- Teste todos os casos possíveis
- Adicione validação de entrada
- Melhore a interface do usuário
- Documente como usar o projeto

---

## 🚀 Como Usar Este Material

1. **Escolha um projeto** que combine com o nível de conhecimento que você tem
2. **Leia os requisitos** e funcionalidades esperadas
3. **Planeje a solução** antes de começar a codificar
4. **Implemente passo a passo**, testando cada parte
5. **Expanda o projeto** com suas próprias ideias

---

[← Voltar ao Índice Principal](../README.md)
