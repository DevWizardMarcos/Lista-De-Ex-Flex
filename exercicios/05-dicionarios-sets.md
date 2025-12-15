# 🗂️ Exercícios - Dicionários e Sets

Domine manipulação de dados com dicionários e conjuntos (sets) em Python.

---

## 📖 DICIONÁRIOS - Métodos Básicos

### 1. Agenda de Contatos Simples
**Descrição:** Crie um dicionário vazio. Adicione contatos com nome como chave e telefone como valor. Permita buscar, atualizar e remover contatos.

**Métodos trabalhados:** `[]`, `get()`, `pop()`, `update()`

---

### 2. Cadastro de Produtos com Preços
**Descrição:** Crie um dicionário com produtos e seus preços. Aplique um desconto de 10% em todos os produtos e mostre o novo dicionário.

**Métodos trabalhados:** `items()`, `keys()`, `values()`, iteração

---

### 3. Contador de Palavras em Texto
**Descrição:** Receba um texto do usuário. Conte quantas vezes cada palavra aparece usando dicionário.

**Métodos trabalhados:** `get()`, incremento de valores, `setdefault()`

---

### 4. Sistema de Login Simples
**Descrição:** Crie um dicionário com usuários e senhas. Peça login e senha e valide se estão corretos.

**Métodos trabalhados:** `get()`, `in`, verificação de chaves

---

### 5. Estoque de Loja
**Descrição:** Crie um dicionário com produtos e quantidades. Permita adicionar, remover e atualizar quantidades. Mostre produtos em falta (quantidade = 0).

**Métodos trabalhados:** `update()`, `pop()`, `items()`

---

### 6. Conversor de Moedas
**Descrição:** Crie um dicionário com taxas de câmbio (ex: USD: 5.20, EUR: 6.10). Peça um valor em reais e converta para todas as moedas.

**Métodos trabalhados:** `items()`, operações matemáticas

---

### 7. Notas de Alunos com Dicionário
**Descrição:** Crie um dicionário com nomes de alunos e suas notas (lista). Calcule a média de cada aluno e mostre quem foi aprovado (média >= 7).

**Métodos trabalhados:** `items()`, valores complexos (listas)

---

### 8. Mesclador de Dicionários
**Descrição:** Crie dois dicionários. Mescle-os de 3 formas diferentes: `update()`, `|` (Python 3.9+), e `{**dict1, **dict2}`.

**Métodos trabalhados:** `update()`, operador `|`, unpacking

---

### 9. Verificador de Chaves
**Descrição:** Crie um dicionário. Peça ao usuário uma chave e verifique se existe de 3 formas: `in`, `get()` e `keys()`.

**Métodos trabalhados:** `in`, `get()`, `keys()`

---

### 10. Removedor de Itens
**Descrição:** Crie um dicionário com 10 itens. Remova itens de diferentes formas: `pop()`, `popitem()`, `del`, `clear()`.

**Métodos trabalhados:** `pop()`, `popitem()`, `del`, `clear()`

---

## 🔧 DICIONÁRIOS - Métodos Avançados

### 11. Dicionário com Valores Padrão
**Descrição:** Crie um sistema que conta votos. Use `setdefault()` para inicializar candidatos automaticamente.

**Métodos trabalhados:** `setdefault()`

---

### 12. Sistema de Pedidos de Restaurante
**Descrição:** Crie um dicionário onde a chave é o número da mesa e o valor é uma lista de pedidos. Adicione, remova e mostre pedidos por mesa.

**Métodos trabalhados:** `setdefault()`, listas como valores

---

### 13. Cópia de Dicionário Profunda
**Descrição:** Crie um dicionário com valores aninhados (outro dicionário dentro). Faça cópias rasas e profundas e mostre a diferença.

**Métodos trabalhados:** `copy()`, `deepcopy()`

---

### 14. Dicionário de Dicionários
**Descrição:** Crie um sistema de cadastro onde cada pessoa é um dicionário com {nome, idade, cidade}. Armazene várias pessoas em um dicionário principal.

**Métodos trabalhados:** Dicionários aninhados, `items()`

---

### 15. Filtrador de Dicionário
**Descrição:** Crie um dicionário com produtos e preços. Crie um novo dicionário apenas com produtos acima de R$50.

**Métodos trabalhados:** Dictionary comprehension, `items()`

---

### 16. Inversor de Dicionário
**Descrição:** Crie um dicionário onde chaves são países e valores são capitais. Crie um novo dicionário invertido (capitais como chaves).

**Métodos trabalhados:** Dictionary comprehension, `items()`

---

### 17. Ordenador de Dicionário
**Descrição:** Crie um dicionário com nomes e idades. Ordene por idade (crescente e decrescente) e por nome (alfabeticamente).

**Métodos trabalhados:** `sorted()`, `items()`, `key=lambda`

---

### 18. Buscador por Valor
**Descrição:** Crie um dicionário. Peça um valor ao usuário e mostre todas as chaves que têm aquele valor.

**Métodos trabalhados:** `items()`, busca reversa

---

### 19. Agrupador de Dados
**Descrição:** Receba uma lista de pessoas com idade. Agrupe por faixa etária: criança (<12), adolescente (12-17), adulto (18-59), idoso (60+).

**Métodos trabalhados:** `setdefault()`, lógica de agrupamento

---

### 20. Gerador de Relatório
**Descrição:** Crie um dicionário com vendas mensais. Calcule total do ano, mês com maior/menor venda, e média mensal.

**Métodos trabalhados:** `values()`, `items()`, `max()`, `min()`

---

## 📊 DICIONÁRIOS - Dictionary Comprehension

### 21. Quadrados de Números
**Descrição:** Crie um dicionário onde as chaves são números de 1 a 10 e os valores são seus quadrados.

**Sintaxe:** `{k: v for k, v in ...}`

---

### 22. Filtro de Números Pares
**Descrição:** Dado um dicionário com números, crie outro apenas com os pares.

**Sintaxe:** `{k: v for k, v in dict.items() if ...}`

---

### 23. Conversor de Temperatura
**Descrição:** Crie um dicionário com temperaturas em Celsius. Crie outro com conversão para Fahrenheit.

**Sintaxe:** Dictionary comprehension com fórmula

---

### 24. Inicializador de Dicionário
**Descrição:** Dada uma lista de produtos, crie um dicionário onde todos começam com estoque = 0.

**Sintaxe:** `{item: 0 for item in lista}`

---

### 25. Classificador de Notas
**Descrição:** Dado dicionário com notas, crie outro com "Aprovado"/"Reprovado" baseado na nota.

**Sintaxe:** Comprehension com condição

---

## 🎯 SETS - Criação e Métodos Básicos

### 26. Removedor Automático de Duplicatas
**Descrição:** Receba uma lista com valores repetidos. Converta para set e mostre sem duplicatas.

**Conceitos:** Conversão `set()`, unicidade

---

### 27. Validador de Itens Únicos
**Descrição:** Receba uma lista de CPFs. Use set para verificar se há CPFs duplicados.

**Conceitos:** Comparação de tamanhos `len(lista)` vs `len(set(lista))`

---

### 28. Adicionador e Removedor
**Descrição:** Crie um set vazio. Adicione itens com `add()`. Remova com `remove()`, `discard()` e mostre a diferença.

**Métodos trabalhados:** `add()`, `remove()`, `discard()`, `pop()`

---

### 29. Limpador de Set
**Descrição:** Crie um set com 10 elementos. Limpe completamente usando `clear()`.

**Métodos trabalhados:** `clear()`

---

### 30. Verificador de Pertencimento
**Descrição:** Crie um set de linguagens de programação. Peça uma linguagem ao usuário e verifique se está no set.

**Conceitos:** Operador `in`, busca O(1)

---

## 🔀 SETS - Operações de Conjunto

### 31. União de Grupos
**Descrição:** Crie dois sets de alunos (turma A e turma B). Mostre todos os alunos únicos (união).

**Métodos trabalhados:** `union()`, operador `|`

---

### 32. Interseção de Interesses
**Descrição:** Crie dois sets de hobbies de duas pessoas. Mostre os hobbies em comum.

**Métodos trabalhados:** `intersection()`, operador `&`

---

### 33. Diferença de Conjuntos
**Descrição:** Crie set de produtos em estoque e set de produtos vendidos. Mostre produtos que ainda não foram vendidos.

**Métodos trabalhados:** `difference()`, operador `-`

---

### 34. Diferença Simétrica
**Descrição:** Crie dois sets de alimentos (pessoa 1 e pessoa 2 gostam). Mostre alimentos que apenas uma pessoa gosta.

**Métodos trabalhados:** `symmetric_difference()`, operador `^`

---

### 35. Verificador de Subconjunto
**Descrição:** Crie um set de permissões de admin e outro de usuário comum. Verifique se usuário comum é subconjunto de admin.

**Métodos trabalhados:** `issubset()`, `issuperset()`

---

### 36. Verificador de Disjunção
**Descrição:** Crie dois sets de horários disponíveis. Verifique se não há horários em comum (são disjuntos).

**Métodos trabalhados:** `isdisjoint()`

---

### 37. Atualização de Sets
**Descrição:** Crie um set inicial. Atualize-o com novos elementos usando diferentes métodos.

**Métodos trabalhados:** `update()`, `|=`, `add()`

---

### 38. Remoção por Interseção
**Descrição:** Crie um set de tarefas pendentes. Remova as tarefas que foram concluídas (outro set).

**Métodos trabalhados:** `difference_update()`, `-=`

---

## 🎓 SETS - Exercícios Avançados

### 39. Validador de Anagramas
**Descrição:** Receba duas palavras. Use sets para verificar se são anagramas (mesmas letras).

**Conceitos:** Conversão de string para set

---

### 40. Contador de Letras Únicas
**Descrição:** Receba uma frase. Mostre quantas letras diferentes foram usadas.

**Conceitos:** `set()` em strings, `len()`

---

### 41. Comparador de Listas
**Descrição:** Receba duas listas. Mostre: elementos únicos da primeira, únicos da segunda, elementos comuns, todos os elementos.

**Conceitos:** Todas as operações de conjunto

---

### 42. Sistema de Tags
**Descrição:** Crie um sistema onde cada post tem tags (set). Implemente busca por posts que contêm determinada tag.

**Conceitos:** Sets aninhados, busca

---

### 43. Frozen Set Imutável
**Descrição:** Crie um frozenset com dados fixos (ex: dias da semana). Tente modificar e mostre que é imutável.

**Conceitos:** `frozenset()`, imutabilidade

---

## 🚀 DESAFIOS COMBINADOS

### 44. Sistema de Votação
**Descrição:** Use dicionário para contar votos e set para garantir que cada CPF vote apenas uma vez.

**Combina:** Dicionário + Set, validação

---

### 45. Agenda com E-mails Únicos
**Descrição:** Crie dicionário de contatos. Use set para garantir que não há e-mails duplicados.

**Combina:** Dicionário + Set de valores

---

### 46. Inventário de Jogo
**Descrição:** Use dicionário para itens com quantidade. Use set para rastreamento de itens únicos coletados.

**Combina:** Dicionário + Set paralelo

---

### 47. Sistema de Permissões de Usuários
**Descrição:** Dicionário onde chave é usuário e valor é set de permissões. Implemente verificação de acesso.

**Combina:** Dicionário com set como valor

---

### 48. Análise de Frequência de Palavras
**Descrição:** Receba um texto. Use dicionário para contar frequência e set para palavras únicas.

**Combina:** Dicionário + Set, análise de texto

---

### 49. Catálogo de Filmes por Gênero
**Descrição:** Dicionário onde chave é gênero e valor é set de filmes. Implemente busca e recomendação.

**Combina:** Dicionário + Set, operações de união

---

### 50. Comparador de Dicionários
**Descrição:** Dados dois dicionários, mostre: chaves únicas de cada um, chaves em comum, valores diferentes para mesmas chaves.

**Combina:** Sets a partir de `keys()`, comparação

---

## 📋 Tabela de Referência Rápida

### Métodos de Dicionário:
```python
dict[key]           # Acessa valor
get(key, default)   # Acessa com valor padrão
keys()              # Retorna chaves
values()            # Retorna valores
items()             # Retorna pares
update(dict2)       # Mescla dicionários
pop(key)            # Remove e retorna
setdefault(k, v)    # Define se não existe
```

### Métodos de Set:
```python
add(item)           # Adiciona
remove(item)        # Remove (erro se não existe)
discard(item)       # Remove (sem erro)
union() ou |        # União
intersection() ou & # Interseção
difference() ou -   # Diferença
symmetric_diff ou ^ # Diferença simétrica
```

### Quando usar cada estrutura?

| Estrutura | Quando Usar | Características |
|-----------|-------------|-----------------|
| **Lista** | Ordem importa, pode repetir | Mutável, ordenada |
| **Tupla** | Dados fixos, imutável | Imutável, ordenada |
| **Dicionário** | Pares chave-valor | Mutável, busca O(1) |
| **Set** | Valores únicos | Mutável, sem duplicatas |

---

[← Voltar ao Índice Principal](../README.md)
