# 📚 Exercícios - Listas e Tuplas

Domine métodos, fatiamento e manipulação de dados com listas e tuplas em Python.

---

## 📋 LISTAS - Métodos e Manipulação

### 1. Organizador de Playlist Musical
**Descrição:** Crie uma playlist vazia. Permita adicionar músicas, remover, inserir em posição específica e exibir a lista completa.

**Métodos trabalhados:** `append()`, `remove()`, `insert()`, `pop()`, `clear()`

---

### 2. Gerenciador de Notas de Alunos
**Descrição:** Peça 5 notas de um aluno. Calcule a média, mostre a maior e menor nota, e ordene as notas em ordem crescente e decrescente.

**Métodos trabalhados:** `sort()`, `reverse()`, `max()`, `min()`, `sum()`

---

### 3. Lista de Tarefas com Prioridade
**Descrição:** Crie uma lista de tarefas. Permita adicionar no início (alta prioridade) ou no final (baixa prioridade). Mostre a primeira e última tarefa.

**Métodos trabalhados:** `insert()`, `append()`, indexação

---

### 4. Contador de Itens em Lista de Compras
**Descrição:** Receba uma lista de produtos (podem repetir). Conte quantas vezes cada item aparece.

**Métodos trabalhados:** `count()`, `set()`

---

### 5. Removedor de Duplicatas Inteligente
**Descrição:** Receba uma lista com valores repetidos. Crie uma nova lista sem duplicatas, mantendo a ordem original.

**Métodos trabalhados:** `append()`, verificação com `in`

---

### 6. Verificador de Item na Lista
**Descrição:** Peça uma lista de frutas. Depois pergunte qual fruta o usuário quer buscar. Informe se existe e em qual posição.

**Métodos trabalhados:** `index()`, `in`, tratamento de erro

---

### 7. Inversor de Lista
**Descrição:** Receba uma lista de palavras e mostre ela invertida de 3 formas diferentes.

**Métodos trabalhados:** `reverse()`, `[::-1]`, `reversed()`

---

### 8. Concatenador de Listas
**Descrição:** Crie duas listas (ex: alimentos e bebidas). Una-as de diferentes formas e mostre o resultado.

**Métodos trabalhados:** `extend()`, `+`, `+=`

---

### 9. Estatísticas de Lista Numérica
**Descrição:** Receba uma lista de números. Mostre: quantidade de elementos, soma, média, maior, menor, e quantos são pares/ímpares.

**Métodos trabalhados:** `len()`, `sum()`, `max()`, `min()`

---

### 10. Copiador de Lista Profunda
**Descrição:** Crie uma lista e faça cópias de diferentes formas. Modifique as cópias e mostre a diferença entre cópia rasa e profunda.

**Métodos trabalhados:** `copy()`, `[:]`, `=`, `deepcopy()`

---

## 🔪 LISTAS - Fatiamento (Slicing)

### 11. Extrator de Primeiros e Últimos
**Descrição:** Receba uma lista de nomes. Mostre os 3 primeiros, os 3 últimos e do meio.

**Fatiamento:** `[:3]`, `[-3:]`, `[2:-2]`

---

### 12. Pulador de Elementos
**Descrição:** Crie uma lista de números de 1 a 20. Mostre apenas os números pares usando fatiamento.

**Fatiamento:** `[::2]`, `[1::2]`

---

### 13. Inversor com Fatiamento
**Descrição:** Receba uma palavra e inverta usando fatiamento. Funciona com listas também!

**Fatiamento:** `[::-1]`

---

### 14. Separador de Metades
**Descrição:** Receba uma lista qualquer e divida em duas metades usando fatiamento.

**Fatiamento:** `[:len(lista)//2]`, `[len(lista)//2:]`

---

### 15. Fatiador Avançado
**Descrição:** Dada uma lista de 20 elementos, mostre: elementos de índice par, de 3 em 3, e invertidos de 2 em 2.

**Fatiamento:** `[::2]`, `[::3]`, `[::-2]`

---

### 16. Substituidor de Fatia
**Descrição:** Crie uma lista e substitua uma fatia inteira por novos valores.

**Fatiamento:** `lista[2:5] = [nova, lista]`

---

### 17. Extrator de Extremos
**Descrição:** Dada uma lista, remova o primeiro e último elemento usando fatiamento.

**Fatiamento:** `[1:-1]`

---

### 18. Copiador com Fatiamento
**Descrição:** Crie uma lista e faça uma cópia usando fatiamento. Compare com atribuição simples.

**Fatiamento:** `lista[:]`

---

## 🔒 TUPLAS - Imutabilidade e Métodos

### 19. Coordenadas Geográficas
**Descrição:** Crie tuplas com latitude e longitude de 5 cidades. Armazene em uma lista e mostre todas.

**Conceitos:** Criação de tuplas, tuplas aninhadas

---

### 20. Dados Pessoais Imutáveis
**Descrição:** Crie uma tupla com (nome, idade, CPF). Tente modificar e mostre que não é possível.

**Conceitos:** Imutabilidade, erro de atribuição

---

### 21. Contador de Elementos em Tupla
**Descrição:** Crie uma tupla com valores repetidos (ex: dados de um dado de 6 faces jogado 20 vezes). Conte quantas vezes cada número aparece.

**Métodos trabalhados:** `count()`

---

### 22. Localizador de Índice em Tupla
**Descrição:** Crie uma tupla com dias da semana. Pergunte qual dia o usuário quer buscar e mostre o índice.

**Métodos trabalhados:** `index()`, tratamento de erro

---

### 23. Desempacotamento de Tuplas
**Descrição:** Crie uma tupla com (produto, preço, quantidade). Desempacote em variáveis separadas e mostre cada uma.

**Conceitos:** Unpacking, `*args`

---

### 24. Troca de Valores com Tuplas
**Descrição:** Use tuplas para trocar valores de variáveis sem usar variável auxiliar.

**Conceitos:** `a, b = b, a`

---

### 25. Tupla de Tuplas - Tabela de Dados
**Descrição:** Crie uma tupla contendo tuplas (simulando uma tabela) com dados de produtos (nome, preço, estoque). Percorra e exiba formatado.

**Conceitos:** Tuplas aninhadas, iteração

---

### 26. Conversão Lista ↔ Tupla
**Descrição:** Crie uma lista mutável, ordene e converta para tupla. Depois converta uma tupla em lista para modificar.

**Conceitos:** `tuple()`, `list()`

---

### 27. Tupla como Chave de Dicionário
**Descrição:** Crie um dicionário usando tuplas como chaves (ex: coordenadas) e valores como nomes de locais.

**Conceitos:** Tuplas imutáveis em dicionários

---

### 28. Concatenação e Repetição de Tuplas
**Descrição:** Crie duas tuplas e una-as. Depois repita uma tupla 5 vezes.

**Conceitos:** Operadores `+` e `*`

---

## ✂️ TUPLAS - Fatiamento

### 29. Fatiador de Tupla de Meses
**Descrição:** Crie uma tupla com os 12 meses. Mostre: primeiro trimestre, último semestre, meses de forma invertida.

**Fatiamento:** `[:3]`, `[6:]`, `[::-1]`

---

### 30. RGB e RGBA com Fatiamento
**Descrição:** Crie tuplas representando cores RGB. Extraia apenas os valores R e G usando fatiamento.

**Fatiamento:** `[:2]`

---

### 31. Histórico de Transações
**Descrição:** Crie uma tupla com 10 valores de transações. Mostre as 5 mais recentes e as 5 mais antigas.

**Fatiamento:** `[-5:]`, `[:5]`

---

### 32. Ignorar Primeiro e Último
**Descrição:** Dada uma tupla de números, mostre todos exceto o primeiro e o último.

**Fatiamento:** `[1:-1]`

---

## 🚀 DESAFIOS COMBINADOS

### 33. Conversor de Lista para Tupla Sem Duplicatas
**Descrição:** Receba uma lista com duplicatas, remova-as e converta para tupla ordenada.

**Combina:** Listas, sets, tuplas, métodos

---

### 34. Comparador de Listas e Tuplas
**Descrição:** Crie uma lista e uma tupla com os mesmos dados. Compare desempenho, mutabilidade e uso de memória.

**Combina:** Conceitos teóricos aplicados

---

### 35. Sistema de Registro de Alunos
**Descrição:** Use listas para nomes (mutáveis) e tuplas para dados fixos como (matrícula, data_nascimento). Permita adicionar e remover alunos.

**Combina:** Listas, tuplas, estruturas mistas

---

### 36. Fatiamento Cruzado
**Descrição:** Dada uma lista de 20 elementos, crie uma tupla com elementos de índice ímpar invertidos.

**Combina:** Fatiamento avançado, conversão

---

### 37. Ordenação Personalizada com Tuplas
**Descrição:** Crie uma lista de tuplas (nome, idade). Ordene por idade e depois por nome.

**Combina:** `sorted()`, `key=lambda`

---

### 38. Menu Interativo com Listas e Tuplas
**Descrição:** Crie um menu que permita:
- Adicionar itens a uma lista
- Visualizar lista
- Converter lista em tupla
- Tentar modificar tupla
- Fatiamento interativo

**Combina:** Todos os conceitos

---

## 📊 Tabela de Referência Rápida

### Métodos de Lista:
```python
append()    # Adiciona ao final
insert()    # Adiciona em posição
remove()    # Remove por valor
pop()       # Remove por índice
clear()     # Limpa lista
sort()      # Ordena in-place
reverse()   # Inverte in-place
count()     # Conta ocorrências
index()     # Acha índice
copy()      # Copia lista
extend()    # Une listas
```

### Métodos de Tupla:
```python
count()     # Conta ocorrências
index()     # Acha índice
# Apenas 2 métodos! Tuplas são imutáveis.
```

### Fatiamento Universal [início:fim:passo]:
```python
lista[0:5]      # Do 0 ao 4
lista[:3]       # 3 primeiros
lista[3:]       # Do 3 até o fim
lista[-3:]      # 3 últimos
lista[::2]      # De 2 em 2
lista[::-1]     # Invertido
lista[1:-1]     # Remove extremos
```

---

[← Voltar ao Índice Principal](../README.md)
