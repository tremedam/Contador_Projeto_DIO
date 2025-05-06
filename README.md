# 🚀 Desafio: Controle de Fluxo em Java

Este projeto foi desenvolvido como parte da **Trilha Java Básico** da [DIO (Digital Innovation One)](https://www.dio.me), sob orientação do instrutor **Gleyson Sampaio**.

## 🧠 Objetivo do Desafio

Colocar em prática os conhecimentos sobre **controle de fluxo** em Java, criando um sistema simples que:

- Recebe dois parâmetros inteiros via terminal.
- Imprime uma sequência de números com base na diferença entre os parâmetros.
- Lança uma exceção customizada caso os parâmetros sejam inválidos.

---

## 🛠️ Funcionalidades Implementadas

✅ Leitura de dois números inteiros via terminal  
✅ Validação dos parâmetros com exceção customizada  
✅ Impressão dos números com uso de laço `for`  
✅ Implementação da classe `ParametrosInvalidosException`  
✅ Projeto modular e de fácil leitura

---

## 📄 Exemplo de Execução

**Entrada:**
 
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
15


**Saída:**

Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3


**Entrada inválida:**

Digite o primeiro parâmetro:
20
Digite o segundo parâmetro:
10


**Saída:**

O segundo parâmetro deve ser maior que o primeiro


---

## 📂 Estrutura do Projeto

DesafioControleFluxo/
├── Contador.java
└── ParametrosInvalidosException.java


- `Contador.java`: contém a lógica principal de leitura, validação e impressão dos números.
- `ParametrosInvalidosException.java`: classe que define a exceção personalizada lançada em caso de erro de entrada.

---

## 👨‍💻 Tecnologias Utilizadas

- Java
- VSCode
- Terminal para entrada de dados

---

## ✍️ Autor

Projeto desenvolvido por **Thiago Fellipe S. Dias** durante a trilha **Java** na [DIO](https://www.dio.me).
