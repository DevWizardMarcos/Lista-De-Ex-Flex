# 📚 Recursos e Referências

Material complementar para auxiliar nos estudos.

---

## 📖 Guias de Referência Rápida

### Operadores e Estruturas

#### Operadores de Comparação
```python
==  # Igual a
!=  # Diferente de
>   # Maior que
<   # Menor que
>=  # Maior ou igual
<=  # Menor ou igual
```

#### Operadores Lógicos
```python
and  # E lógico
or   # Ou lógico
not  # Não lógico
```

#### Estruturas de Controle
```python
# If-Elif-Else
if condicao:
    # código
elif outra_condicao:
    # código
else:
    # código

# While Loop
while condicao:
    # código
    if sair:
        break
    if pular:
        continue

# For Loop
for item in iteravel:
    # código
```

---

## 🗂️ Estruturas de Dados

### Quando Usar Cada Uma?

| Estrutura | Quando Usar | Características |
|-----------|-------------|-----------------|
| **Lista** | Ordem importa, pode repetir | Mutável, ordenada, acesso por índice |
| **Tupla** | Dados fixos, imutável | Imutável, ordenada, mais rápida |
| **Dicionário** | Pares chave-valor, busca rápida | Mutável, não ordenado*, busca O(1) |
| **Set** | Valores únicos, operações matemáticas | Mutável, não ordenado, sem duplicatas |

*A partir do Python 3.7+, dicionários mantêm ordem de inserção

### Complexidade de Operações

| Operação | Lista | Tupla | Dict | Set |
|----------|-------|-------|------|-----|
| Acesso por índice | O(1) | O(1) | - | - |
| Busca | O(n) | O(n) | O(1) | O(1) |
| Inserção | O(1)* | - | O(1) | O(1) |
| Remoção | O(n) | - | O(1) | O(1) |

*O(1) apenas no final da lista

---

## 🔧 Métodos Mais Usados

### Listas
```python
lista.append(item)      # Adiciona ao final
lista.insert(i, item)   # Adiciona em posição
lista.remove(item)      # Remove primeira ocorrência
lista.pop(i)            # Remove e retorna item
lista.sort()            # Ordena in-place
lista.reverse()         # Inverte in-place
len(lista)              # Tamanho
item in lista           # Verifica existência
```

### Dicionários
```python
dict[key] = value       # Adiciona/atualiza
dict.get(key, default)  # Busca com padrão
dict.keys()             # Todas as chaves
dict.values()           # Todos os valores
dict.items()            # Pares chave-valor
dict.pop(key)           # Remove e retorna
key in dict             # Verifica chave
```

### Sets
```python
set.add(item)           # Adiciona item
set.remove(item)        # Remove item (erro se não existe)
set.discard(item)       # Remove item (sem erro)
set1 | set2             # União
set1 & set2             # Interseção
set1 - set2             # Diferença
set1 ^ set2             # Diferença simétrica
```

---

## 🎯 Boas Práticas

### Nomenclatura
```python
# Use snake_case para variáveis e funções
minha_variavel = 10
def calcular_media():
    pass

# Use PascalCase para classes
class MinhaClasse:
    pass

# Use UPPER_CASE para constantes
TAXA_JUROS = 0.05
```

### Estrutura de Código
```python
# Organize imports no topo
import os
import sys
from datetime import datetime

# Depois constantes
MAX_TENTATIVAS = 3

# Depois funções e classes
def minha_funcao():
    pass

# Por fim, código principal
if __name__ == "__main__":
    # código principal
    pass
```

### Validação de Entrada
```python
# Sempre valide entrada do usuário
try:
    idade = int(input("Digite sua idade: "))
    if idade < 0:
        print("Idade inválida!")
except ValueError:
    print("Por favor, digite um número!")
```

---

## 📝 Templates Úteis

### Menu Interativo
```python
def mostrar_menu():
    print("\n=== MENU ===")
    print("1. Opção 1")
    print("2. Opção 2")
    print("3. Sair")
    return input("Escolha uma opção: ")

while True:
    opcao = mostrar_menu()
    
    if opcao == "1":
        # código opção 1
        pass
    elif opcao == "2":
        # código opção 2
        pass
    elif opcao == "3":
        print("Saindo...")
        break
    else:
        print("Opção inválida!")
```

### Validação de Entrada
```python
def obter_numero(mensagem, minimo=None, maximo=None):
    while True:
        try:
            numero = float(input(mensagem))
            if minimo is not None and numero < minimo:
                print(f"Valor deve ser maior que {minimo}")
                continue
            if maximo is not None and numero > maximo:
                print(f"Valor deve ser menor que {maximo}")
                continue
            return numero
        except ValueError:
            print("Digite um número válido!")
```

### Salvar/Carregar JSON
```python
import json

def salvar_dados(dados, arquivo):
    with open(arquivo, 'w', encoding='utf-8') as f:
        json.dump(dados, f, indent=4, ensure_ascii=False)

def carregar_dados(arquivo):
    try:
        with open(arquivo, 'r', encoding='utf-8') as f:
            return json.load(f)
    except FileNotFoundError:
        return {}
```

---

## 🐛 Debugging

### Print Debugging
```python
# Use prints informativos
print(f"Valor de x: {x}")
print(f"Tipo de dados: {type(x)}")
print(f"Tamanho da lista: {len(lista)}")

# Debug condicional
DEBUG = True
if DEBUG:
    print("Entrando na função...")
```

### Erros Comuns

#### IndentationError
```python
# ❌ Errado - indentação inconsistente
if True:
print("Isso vai dar erro")

# ✅ Correto
if True:
    print("Isso funciona")
```

#### KeyError em Dicionários
```python
# ❌ Pode dar erro
valor = dicionario[chave]

# ✅ Seguro
valor = dicionario.get(chave, "valor_padrao")
```

#### IndexError em Listas
```python
# ❌ Pode dar erro
item = lista[10]

# ✅ Seguro
if len(lista) > 10:
    item = lista[10]
```

---

## 📚 Links Úteis

### Documentação Oficial
- [Python.org - Documentação](https://docs.python.org/pt-br/3/)
- [PEP 8 - Style Guide](https://pep8.org/)

### Tutoriais e Cursos
- [W3Schools Python](https://www.w3schools.com/python/)
- [Real Python](https://realpython.com/)
- [Python Brasil](https://python.org.br/)

### Ferramentas
- [Python Tutor - Visualizador](http://pythontutor.com/)
- [Repl.it - IDE Online](https://replit.com/)

### Comunidades
- [Python Brasil no Discord](https://discord.gg/python-brasil)
- [Stack Overflow em Português](https://pt.stackoverflow.com/questions/tagged/python)

---

## 🎓 Progressão de Estudos Sugerida

### Nível Iniciante
1. ✅ Variáveis e tipos de dados
2. ✅ Operadores e expressões
3. ✅ Estruturas condicionais (if/elif/else)
4. ✅ Laços de repetição (while/for)
5. ✅ Listas básicas

### Nível Intermediário
1. ✅ Listas avançadas e fatiamento
2. ✅ Tuplas
3. ✅ Dicionários e Sets
4. ✅ Funções
5. ✅ Módulos básicos
6. ✅ Manipulação de strings
7. ✅ Tratamento de erros (try/except)

### Nível Avançado
1. ✅ Funções avançadas (*args, **kwargs, lambda)
2. ✅ List/Dict comprehensions
3. ✅ Manipulação de arquivos
4. ✅ JSON e APIs
5. ✅ Orientação a Objetos (Classes)
6. ✅ Decoradores
7. ✅ Geradores e Iteradores

---

## 💡 Dicas de Estudo

### Como Aproveitar Melhor os Exercícios

1. **Leia o enunciado com atenção** - Entenda o que é pedido antes de começar
2. **Planeje antes de codificar** - Pense na lógica e nos passos necessários
3. **Comece simples** - Implemente a versão básica primeiro
4. **Teste progressivamente** - Teste cada parte conforme desenvolve
5. **Refatore** - Melhore o código depois que funcionar
6. **Documente** - Adicione comentários explicando a lógica

### Quando Você Travar

1. **Revise conceitos** - Volte ao material teórico
2. **Divida o problema** - Quebre em partes menores
3. **Use print()** - Visualize o que está acontecendo
4. **Pesquise** - Busque exemplos similares
5. **Peça ajuda** - Discuta com colegas ou professor
6. **Descanse** - Às vezes, a solução vem depois de uma pausa

---

[← Voltar ao Índice Principal](../README.md)
