# 💳 Sistema de Simulação Financeira

> Projeto desenvolvido durante os estudos de Java com o objetivo de praticar e consolidar os principais conceitos da linguagem através da criação de uma aplicação de console.

---

# 📖 Sobre o projeto

O **Sistema de Simulação Financeira** simula uma compra realizada por um cliente em uma loja.

Durante a execução, o usuário informa seus dados pessoais e as informações da compra. O sistema realiza conversões de tipos, manipula Strings, executa cálculos financeiros, utiliza diferentes operadores da linguagem Java e apresenta um relatório completo no final da execução.

Este projeto foi desenvolvido utilizando **apenas os conteúdos estudados na primeira etapa do curso**, sem o uso de estruturas condicionais (`if/else`), laços de repetição (`for`, `while`), métodos próprios ou Programação Orientada a Objetos (POO).

O principal objetivo é demonstrar domínio dos fundamentos da linguagem Java por meio de um projeto prático e organizado.

---

# 🎯 Objetivos do projeto

Este projeto foi criado para praticar:

* Declaração de variáveis e constantes (`final`)
* Inferência de tipos (`var`)
* Tipos primitivos
* Wrappers (`Integer`, `Double`, etc.)
* Conversões entre tipos primitivos (Casting)
* Conversões entre String e números
* Entrada de dados com `Scanner`
* Manipulação de Strings
* Operadores aritméticos
* Operadores relacionais
* Operadores lógicos
* Operadores unários
* Operadores de atribuição
* Operador ternário
* Precedência dos operadores
* Organização e legibilidade do código

---

# ⚙️ Funcionalidades

O sistema permite:

* Cadastrar os dados do cliente.
* Registrar informações da compra.
* Converter dados entre diferentes tipos.
* Manipular textos utilizando métodos da classe `String`.
* Calcular subtotal, taxas, descontos e valor final da compra.
* Calcular o saldo restante do cliente após a compra.
* Realizar comparações utilizando operadores relacionais.
* Criar expressões utilizando operadores lógicos.
* Gerar mensagens através do operador ternário.
* Exibir um relatório organizado no console.

---

# 🔄 Fluxo de funcionamento

O programa segue a seguinte sequência:

### 1. Cadastro do cliente

O usuário informa:

* Nome completo
* Idade
* Salário
* Valor do produto
* Quantidade de produtos
* Cliente Premium (SIM ou NÃO)

> Todos os valores numéricos são digitados inicialmente como **String**.

---

### 2. Conversão dos dados

O sistema converte os valores para seus respectivos tipos utilizando Wrappers.

Exemplos:

* `String → int`
* `String → double`
* `int → String`
* `double → int` (Casting)

---

### 3. Manipulação de Strings

São realizadas diversas operações com o nome informado pelo usuário, como:

* Quantidade de caracteres
* Nome em maiúsculo
* Nome em minúsculo
* Primeira letra
* Última letra

Além disso, é feita a comparação correta utilizando `equals()` e `equalsIgnoreCase()`.

---

### 4. Cálculos financeiros

O sistema calcula:

* Valor total da compra
* Taxas
* Descontos
* Total final
* Saldo restante

---

### 5. Operadores

Durante o desenvolvimento são utilizados diversos operadores da linguagem:

* Aritméticos
* Relacionais
* Lógicos
* Unários
* Atribuição
* Ternário

Todos aplicados em situações semelhantes às encontradas em sistemas reais.

---

### 6. Relatório Final

Ao finalizar todos os cálculos, o programa apresenta um relatório completo contendo todas as informações processadas.

---

# 📄 Exemplo do relatório

```text
==================================================
             RELATÓRIO DA COMPRA
==================================================

DADOS DO CLIENTE

Nome:
Idade:
Cliente Premium:

--------------------------------------------------

DADOS DA COMPRA

Valor do produto:
Quantidade:
Subtotal:
Taxa:
Desconto:
Total da compra:

--------------------------------------------------

SITUAÇÃO FINANCEIRA

Salário:
Saldo restante:

--------------------------------------------------

INFORMAÇÕES DA STRING

Quantidade de caracteres:
Nome em maiúsculo:
Nome em minúsculo:
Primeira letra:
Última letra:

--------------------------------------------------

TESTES RELACIONAIS

Cliente é maior de idade:
Compra é maior que o salário:
Quantidade é diferente de zero:
Salário é igual ao valor da compra:

--------------------------------------------------

TESTES LÓGICOS

Cliente é maior de idade e Premium:
Cliente é Premium ou possui saldo suficiente:
Cliente não é Premium:
Cliente possui saldo suficiente e compra válida:
Cliente é maior de idade ou compra pequena:

--------------------------------------------------

OPERADOR TERNÁRIO

Categoria do cliente:
Situação da compra:
Maioridade:

==================================================
```

---

# 🛠️ Tecnologias utilizadas

* Java
* Eclipse IDE
* JDK

---

# 📚 Conceitos praticados

## Fundamentos

* Variáveis
* Constantes
* Inferência de tipos
* Tipos primitivos

## Entrada e saída

* Scanner
* Console

## Strings

* Métodos da classe `String`
* Comparação de Strings
* Conversão entre texto e números

## Conversões

* Casting
* `Integer.parseInt()`
* `Double.parseDouble()`
* `Integer.toString()`
* `String.valueOf()`

## Operadores

* Aritméticos
* Relacionais
* Lógicos
* Unários
* Atribuição
* Ternário

---

# 📂 Estrutura do projeto

```text
SistemaFinanceiro/
│
├── src/
│   └── desafiofinal/
│       └── SistemaFinanceiro.java
│
└── README.md
```

---

# 🚀 Como executar

1. Clone este repositório.
2. Abra o projeto na IDE de sua preferência.
3. Execute a classe `SistemaFinanceiro`.
4. Informe os dados solicitados pelo programa.
5. Ao final da execução, visualize o relatório completo gerado no console.

---

# 🎓 Objetivo educacional

Este projeto faz parte da minha jornada de aprendizado em Java.

Seu objetivo é aplicar, na prática, todos os conceitos estudados nos módulos iniciais do curso, desenvolvendo um sistema organizado e próximo de um cenário real, fortalecendo a base necessária para os próximos conteúdos, como estruturas condicionais, laços de repetição e Programação Orientada a Objetos.

---

# 📌 Curso Base

**Fundamentos de Programação com Java**

https://www.udemy.com/course/fundamentos-de-programacao-com-java/

---

## 👨‍💻 Autor

Desenvolvido por **Cainã Haniel** como parte dos estudos em Java.
