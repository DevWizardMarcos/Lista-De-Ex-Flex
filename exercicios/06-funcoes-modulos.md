# 🎯 Exercícios - Funções e Módulos

Domine a criação de funções, módulos e uso de bibliotecas essenciais do Python.

---

## 🔰 FUNÇÕES - Conceitos Básicos

### 1. Minha Primeira Função
**Descrição:** Crie uma função que exibe "Olá, Mundo!" na tela. Chame a função 3 vezes.

**Conceitos:** `def`, chamada de função, `print()`

---

### 2. Função com Parâmetro
**Descrição:** Crie uma função que recebe um nome e exibe "Olá, [nome]!".

**Conceitos:** Parâmetros, argumentos

---

### 3. Calculadora de Soma
**Descrição:** Crie uma função que recebe dois números e retorna a soma.

**Conceitos:** `return`, operações matemáticas

---

### 4. Verificador de Par ou Ímpar
**Descrição:** Crie uma função que recebe um número e retorna "Par" ou "Ímpar".

**Conceitos:** Condicionais dentro de funções, `return`

---

### 5. Calculadora de Idade
**Descrição:** Crie uma função que recebe o ano de nascimento e retorna a idade atual.

**Conceitos:** Importar `datetime`, cálculos

---

### 6. Conversor de Temperatura
**Descrição:** Crie funções `celsius_para_fahrenheit()` e `fahrenheit_para_celsius()`.

**Conceitos:** Múltiplas funções, fórmulas matemáticas

---

### 7. Validador de Senha
**Descrição:** Crie uma função que recebe uma senha e retorna se ela é forte (mínimo 8 caracteres, tem números e letras).

**Conceitos:** Validação, `len()`, métodos de string

---

### 8. Contador de Vogais
**Descrição:** Crie uma função que recebe uma string e retorna quantas vogais existem.

**Conceitos:** Loops dentro de funções, contadores

---

### 9. Gerador de Saudação Personalizada
**Descrição:** Crie uma função que recebe nome e período (manhã/tarde/noite) e retorna saudação apropriada.

**Conceitos:** Múltiplos parâmetros, condicionais

---

### 10. Calculadora Completa
**Descrição:** Crie funções separadas para soma, subtração, multiplicação e divisão. Crie uma função principal que chama as outras.

**Conceitos:** Múltiplas funções, organização de código

---

## 📦 FUNÇÕES - Parâmetros e Argumentos

### 11. Parâmetros Padrão
**Descrição:** Crie uma função `saudar(nome, idioma="português")` que saúda em diferentes idiomas.

**Conceitos:** Argumentos padrão (default)

---

### 12. Múltiplos Retornos
**Descrição:** Crie uma função que recebe uma lista de números e retorna o maior, o menor e a média.

**Conceitos:** Retornar múltiplos valores (tupla)

---

### 13. Função com Lista como Parâmetro
**Descrição:** Crie uma função que recebe uma lista de números e retorna apenas os pares.

**Conceitos:** Listas como parâmetros, list comprehension

---

### 14. Função que Modifica Lista
**Descrição:** Crie uma função que recebe uma lista e adiciona um elemento. Observe como a lista original é modificada.

**Conceitos:** Mutabilidade, passagem por referência

---

### 15. Argumentos Nomeados (Keyword Arguments)
**Descrição:** Crie uma função `criar_perfil(nome, idade, cidade)` e chame usando argumentos nomeados em ordem diferente.

**Conceitos:** `kwargs`, flexibilidade na chamada

---

### 16. *args - Número Variável de Argumentos
**Descrição:** Crie uma função `somar_todos(*numeros)` que soma qualquer quantidade de números passados.

**Conceitos:** `*args`, argumentos variáveis

---

### 17. **kwargs - Argumentos Nomeados Variáveis
**Descrição:** Crie uma função `criar_usuario(**dados)` que aceita qualquer quantidade de informações sobre o usuário.

**Conceitos:** `**kwargs`, dicionário de argumentos

---

### 18. Combinando *args e **kwargs
**Descrição:** Crie uma função que aceita argumentos posicionais e nomeados ao mesmo tempo.

**Conceitos:** `*args`, `**kwargs`, ordem dos parâmetros

---

### 19. Função Recursiva - Fatorial
**Descrição:** Crie uma função recursiva que calcula o fatorial de um número.

**Conceitos:** Recursão, caso base

---

### 20. Função Recursiva - Fibonacci
**Descrição:** Crie uma função recursiva que retorna o N-ésimo número da sequência de Fibonacci.

**Conceitos:** Recursão, otimização

---

## 📚 MÓDULOS - Criação e Importação

### 21. Criando Seu Primeiro Módulo
**Descrição:** Crie um arquivo `matematica.py` com funções de soma, subtração, multiplicação e divisão. Importe e use em outro arquivo.

**Conceitos:** Criação de módulos, `import`

```python
# matematica.py
def somar(a, b):
    return a + b

def subtrair(a, b):
    return a - b

# main.py
import matematica
resultado = matematica.somar(5, 3)
```

---

### 22. Import com Alias
**Descrição:** Importe seu módulo usando um apelido (alias) com `import matematica as mat`.

**Conceitos:** `import ... as`, simplificação de código

---

### 23. From Import
**Descrição:** Importe apenas funções específicas usando `from matematica import somar, subtrair`.

**Conceitos:** `from ... import`, importação seletiva

---

### 24. Import All (*)
**Descrição:** Use `from matematica import *` e entenda os riscos dessa prática.

**Conceitos:** `import *`, namespace pollution

---

### 25. Módulo com Variáveis
**Descrição:** Crie um módulo `config.py` com variáveis de configuração (API_KEY, DATABASE_URL). Importe e use.

**Conceitos:** Variáveis em módulos, configurações

---

### 26. Verificando __name__ == "__main__"
**Descrição:** Crie um módulo que pode ser executado diretamente ou importado, usando a verificação `if __name__ == "__main__":`.

**Conceitos:** `__name__`, `__main__`, execução vs importação

```python
# utils.py
def dobrar(n):
    return n * 2

if __name__ == "__main__":
    print("Testando:", dobrar(5))
```

---

### 27. Módulo com Classe
**Descrição:** Crie um módulo `pessoa.py` com uma classe Pessoa. Importe e instancie em outro arquivo.

**Conceitos:** Classes em módulos, POO

---

### 28. Pacotes (Packages)
**Descrição:** Crie uma pasta `meu_pacote/` com `__init__.py` e vários módulos dentro. Importe do pacote.

**Conceitos:** Pacotes, `__init__.py`, estrutura de projeto

```
meu_pacote/
    __init__.py
    matematica.py
    texto.py
```

---

### 29. Importação Relativa
**Descrição:** Dentro de um pacote, use importação relativa (`from . import modulo`).

**Conceitos:** Importação relativa, `.` e `..`

---

### 30. Recarregando Módulos
**Descrição:** Use `importlib.reload()` para recarregar um módulo modificado sem reiniciar o programa.

**Conceitos:** `importlib`, `reload()`, desenvolvimento dinâmico

---

## 📖 BIBLIOTECAS PADRÃO (STDLIB)

### 31. Math - Operações Matemáticas
**Descrição:** Use o módulo `math` para calcular raiz quadrada, potência, arredondamento, π (pi), e (euler).

**Funções:** `sqrt()`, `pow()`, `ceil()`, `floor()`, `pi`, `e`

```python
import math
raiz = math.sqrt(16)
print(math.pi)
```

---

### 32. Random - Números Aleatórios
**Descrição:** Gere números aleatórios, escolha elementos aleatórios de listas, embaralhe listas.

**Funções:** `random()`, `randint()`, `choice()`, `shuffle()`, `sample()`

```python
import random
numero = random.randint(1, 100)
escolha = random.choice(['pedra', 'papel', 'tesoura'])
```

---

### 33. Datetime - Data e Hora
**Descrição:** Trabalhe com datas atuais, formate datas, calcule diferenças entre datas.

**Funções:** `datetime.now()`, `strftime()`, `timedelta()`

```python
from datetime import datetime, timedelta
agora = datetime.now()
amanha = agora + timedelta(days=1)
print(agora.strftime("%d/%m/%Y"))
```

---

### 34. Time - Medição de Tempo
**Descrição:** Use `time.sleep()` para pausas, `time.time()` para medir performance de código.

**Funções:** `sleep()`, `time()`, `perf_counter()`

```python
import time
inicio = time.time()
# código aqui
fim = time.time()
print(f"Tempo: {fim - inicio}s")
```

---

### 35. OS - Sistema Operacional
**Descrição:** Liste arquivos, crie pastas, obtenha caminho atual, verifique se arquivo existe.

**Funções:** `listdir()`, `mkdir()`, `getcwd()`, `path.exists()`

```python
import os
arquivos = os.listdir('.')
os.mkdir('nova_pasta')
print(os.getcwd())
```

---

### 36. Sys - Sistema Python
**Descrição:** Acesse argumentos da linha de comando, obtenha informações do sistema.

**Funções:** `argv`, `exit()`, `version`, `platform`

```python
import sys
print(sys.argv)  # argumentos da linha de comando
print(sys.version)
```

---

### 37. JSON - Trabalhar com JSON
**Descrição:** Converta dicionários Python para JSON e vice-versa, salve e carregue arquivos JSON.

**Funções:** `dumps()`, `loads()`, `dump()`, `load()`

```python
import json
dados = {'nome': 'João', 'idade': 25}
json_string = json.dumps(dados)
dados_volta = json.loads(json_string)
```

---

### 38. Collections - Estruturas de Dados Especiais
**Descrição:** Use `Counter` para contar elementos, `defaultdict` para valores padrão, `namedtuple` para tuplas nomeadas.

**Tipos:** `Counter`, `defaultdict`, `namedtuple`, `deque`

```python
from collections import Counter
votos = ['A', 'B', 'A', 'C', 'A', 'B']
contagem = Counter(votos)
print(contagem)  # Counter({'A': 3, 'B': 2, 'C': 1})
```

---

### 39. Itertools - Iteradores Avançados
**Descrição:** Crie combinações, permutações, produtos cartesianos, ciclos infinitos.

**Funções:** `combinations()`, `permutations()`, `product()`, `cycle()`

```python
from itertools import combinations
lista = [1, 2, 3]
combos = combinations(lista, 2)
print(list(combos))  # [(1, 2), (1, 3), (2, 3)]
```

---

### 40. Re - Expressões Regulares
**Descrição:** Valide e-mails, extraia padrões de texto, substitua usando regex.

**Funções:** `search()`, `match()`, `findall()`, `sub()`

```python
import re
email = "usuario@example.com"
if re.match(r'^[\w\.-]+@[\w\.-]+\.\w+$', email):
    print("E-mail válido")
```

---

## 📦 GESTÃO DE PACOTES

### 41. Pip - Instalando Pacotes
**Descrição:** Aprenda a usar `pip install`, `pip uninstall`, `pip list`, `pip freeze`.

**Comandos:**
```bash
pip install requests
pip uninstall requests
pip list
pip freeze > requirements.txt
```

---

### 42. Requirements.txt
**Descrição:** Crie um arquivo `requirements.txt` com todas as dependências do projeto.

**Formato:**
```
requests==2.28.1
pandas==1.5.0
numpy==1.23.3
```

---

### 43. Ambientes Virtuais (venv)
**Descrição:** Crie ambientes virtuais isolados para diferentes projetos.

**Comandos:**
```bash
python -m venv meu_ambiente
source meu_ambiente/bin/activate  # Linux/Mac
meu_ambiente\Scripts\activate  # Windows
pip install -r requirements.txt
```

---

## 🎓 BOAS PRÁTICAS

### ✅ Organização de Funções
```python
def funcao_bem_nomeada(parametro_claro):
    """
    Docstring explicando o que a função faz.
    
    Args:
        parametro_claro: Descrição do parâmetro
        
    Returns:
        Descrição do retorno
    """
    # Código aqui
    return resultado
```

### ✅ Estrutura de Projeto
```
meu_projeto/
    ├── src/
    │   ├── __init__.py
    │   ├── main.py
    │   ├── utils.py
    │   └── config.py
    ├── tests/
    │   └── test_utils.py
    ├── requirements.txt
    └── README.md
```

### ✅ Type Hints (Python 3.5+)
```python
def somar(a: int, b: int) -> int:
    return a + b

def buscar_usuario(user_id: int) -> dict:
    return {'id': user_id, 'nome': 'João'}
```

---

## 💡 Dicas
- Use docstrings para documentar suas funções
- Siga PEP 257 para estilo de docstrings
- Prefira funções pequenas e especializadas
- Evite funções com muitos parâmetros
- Use type hints para código mais claro

---

[← Voltar ao Índice Principal](../README.md)
