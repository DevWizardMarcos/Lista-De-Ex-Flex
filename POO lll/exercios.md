

**Desafio 1:**
Implemente parte de um sistema bancário digital. Crie uma classe `ContaBancaria` com um atributo protegido `_saldo`. Desenvolva métodos para depositar valores e visualizar o saldo, simulando operações seguras de uma conta bancária.

---


**Desafio 2:**
Você está desenvolvendo um sistema de autenticação. Crie uma classe `Usuario` com um atributo privado `__senha`. Tente acessar esse atributo fora da classe e observe o comportamento. Em seguida, acesse utilizando name mangling, explicando a importância desse recurso para a segurança dos dados.

---


**Desafio 3:**
Implemente parte de um sistema de e-commerce. Crie uma classe `Produto` com um atributo privado `_preco`. Utilize `@property` para criar um método que retorne o valor do preço, garantindo acesso controlado ao atributo.

---

**Desafio 4:**
Na mesma classe `Produto`, crie um setter com `@preco.setter` que permita alterar o preço apenas se for maior que zero, simulando uma validação de preços em um sistema real.

---

**Desafio 5:**
Implemente um sistema de cadastro de pessoas. Crie uma classe `Pessoa` com um atributo privado `__idade`. Implemente métodos `get_idade()` e `set_idade(valor)` com validação para garantir que a idade nunca seja negativa, como seria exigido em um sistema de RH.

---

---

**Exercício 6:**
Crie uma classe `Professor` e uma classe `Curso`.  
Associe um professor a um curso (sem criar dependência forte entre eles).  
Exiba os dados relacionados.

---


**Exercício 7:**
Crie uma classe `Motor` e uma classe `Carro`.  
O `Carro` deve ter um `Motor` como parte de sua estrutura (composição).  
Crie um objeto `Carro` e mostre as informações do motor.

---


**Exercício 8:**
Crie um sistema que combine:

- Encapsulamento (atributos privados)
- Uso de `@property`
- Relacionamento entre classes (associação ou composição)

Exemplo de ideia:

- Classe `Pedido`
- Classe `Cliente`
- Classe `Produto`

Implemente regras de acesso aos dados e relacione os objetos entre si.

---


Praticar conceitos essenciais de:
- Encapsulamento
- Controle de acesso a atributos
- `@property`
- Getter e Setter
- Associação e Composição

---