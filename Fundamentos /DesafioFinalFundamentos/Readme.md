# 📊 Painel de Desempenho Acadêmico

> Projeto desenvolvido durante os estudos de Java com o objetivo de praticar e consolidar os principais conceitos da linguagem através da criação de uma aplicação de console.

---

## 📖 Sobre o projeto

O **Painel de Desempenho Acadêmico** é uma aplicação de console desenvolvida para praticar os principais fundamentos da linguagem Java.

O sistema simula o acompanhamento do desempenho de um estudante, permitindo cadastrar informações acadêmicas, realizar conversões de tipos, efetuar cálculos, manipular Strings, gerar indicadores e apresentar um relatório organizado ao final da execução.

O projeto foi desenvolvido utilizando apenas os conteúdos estudados nos módulos iniciais do curso, sem estruturas condicionais (`if/else`), laços de repetição (`for`, `while`), métodos próprios ou Programação Orientada a Objetos (POO).

---

## 🎯 Objetivo

Este projeto tem como objetivo praticar os principais fundamentos da linguagem Java estudados até o momento, aplicando-os em um sistema de console semelhante a uma aplicação real.

Durante o desenvolvimento são utilizados conceitos como:

- Variáveis e constantes
- Tipos primitivos
- Wrappers
- Conversões entre tipos
- Scanner
- Manipulação de Strings
- Operadores aritméticos
- Operadores relacionais
- Operadores lógicos
- Operadores unários
- Operadores de atribuição
- Operador ternário
- Organização e legibilidade do código

---

## 1️⃣ Cadastro do estudante

Inicialmente, o sistema solicitará ao usuário as seguintes informações:

### 👤 Dados pessoais

* Nome completo
* Curso
* Idade

### 📚 Informações de estudo

* Horas de estudo por dia
* Quantidade de matérias
* Quantidade de exercícios resolvidos
* Quantidade de vídeos assistidos
* Nota da última prova

> **Observação:** Todos os valores numéricos serão informados inicialmente como **String** e posteriormente convertidos para seus respectivos tipos utilizando Wrappers.

---

## 2️⃣ Conversão dos dados

Após receber todas as informações, o sistema realizará as conversões necessárias para permitir os cálculos.

Conversões utilizadas:

* `String → int`
* `String → double`
* `double → int` (Casting)

Essas conversões permitirão utilizar corretamente os valores em operações matemáticas.

---

## 3️⃣ Geração das estatísticas

Com os dados convertidos, o sistema calculará automaticamente diversas estatísticas.

Serão exibidas as seguintes informações:

* Horas de estudo por dia
* Horas de estudo por semana
* Horas de estudo por mês
* Quantidade de matérias
* Quantidade de exercícios resolvidos
* Quantidade de vídeos assistidos
* Nota da última prova

Todos esses cálculos serão realizados utilizando operadores aritméticos.

---

## 4️⃣ Análise das Strings

Após os cálculos, o sistema realizará algumas manipulações utilizando métodos da classe `String`.

Serão exibidas informações como:

* Quantidade de caracteres do nome
* Quantidade de caracteres do curso
  
* Nome em letras maiúsculas
* Nome em letras minúsculas
  
* Curso em letras maiúsculas
* Curso em letras minúsculas
  
* Primeira letra do nome
* Última letra do nome

---

## 5️⃣ Geração dos indicadores

Em seguida, o sistema criará indicadores utilizando operadores relacionais e operadores lógicos.

Alguns exemplos:

* O aluno é maior de idade?
* Estuda mais de 20 horas por semana?
* A nota é suficiente para aprovação?
* Resolveu mais de 50 exercícios?
* Possui mais de 5 matérias?

Também serão criados indicadores compostos utilizando operadores lógicos (`&&`, `||` e `!`), como:

* Aluno dedicado.
* Aluno muito ativo.
* Necessita aumentar os estudos.
* Possui bom desempenho geral.
* Cumpriu a meta semanal.

Todos esses indicadores apresentarão valores booleanos (`true` ou `false`).

---

## 6️⃣ Classificação do estudante

Com base nos indicadores gerados, o sistema utilizará o operador ternário para apresentar classificações mais amigáveis ao usuário.

Exemplos:

* Situação acadêmica
* Nível de dedicação
* Desempenho geral
* Meta semanal
* Categoria do aluno

---

## 7️⃣ Relatório Final

Após concluir todas as etapas anteriores, o sistema exibirá um painel completo contendo todas as informações processadas.

```text
==================================================
        PAINEL DE DESEMPENHO ACADÊMICO
==================================================

👤 DADOS DO ALUNO

Nome completo:
Curso:
Idade:

--------------------------------------------------

📚 ESTATÍSTICAS

Horas de estudo por dia:
Horas de estudo por semana:
Horas de estudo por mês:

Quantidade de matérias:
Quantidade de exercícios resolvidos:
Quantidade de vídeos assistidos:
Nota da última prova:

--------------------------------------------------

📝 ANÁLISE DAS STRINGS

Quantidade de caracteres do nome:
Quantidade de caracteres do curso:

Nome em maiúsculas:
Nome em minúsculas:

Curso em maiúsculas:
Curso em minúsculas:

Primeira letra do nome:
Última letra do nome:

--------------------------------------------------

📊 INDICADORES

Maior de idade:
Estuda mais de 20 horas por semana:
Nota suficiente para aprovação:
Resolveu mais de 50 exercícios:
Possui mais de 5 matérias:

Aluno dedicado:
Aluno muito ativo:
Necessita aumentar os estudos:
Possui bom desempenho geral:
Cumpriu a meta semanal:

--------------------------------------------------

🏆 CLASSIFICAÇÃO

Situação acadêmica:
Nível de dedicação:
Desempenho geral:
Meta semanal:
Categoria do aluno:

==================================================
```
## 🚀 Como executar

1. Clone este repositório.
2. Abra o projeto no Eclipse ou em outra IDE Java.
3. Execute a classe principal.
4. Informe os dados solicitados no console.
5. Visualize o relatório gerado pelo sistema.

## 🛠️ Tecnologias utilizadas

- Java
- Eclipse IDE
- JDK


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
