# Sistema Bancário em Java

## Sobre o Projeto

Este é um sistema bancário simples desenvolvido em Java, aplicando conceitos de **Programação Orientada a Objetos (POO)**. O sistema permite:

- 🔑 Cadastro de usuário com nome, sobrenome e CPF.
- 💰 Depósitos e saques com validações de saldo.
- 📊 Consulta de saldo formatado corretamente.
- 📆 Registro de transações em um histórico (log de ações).
- ⚡ Tratamento de exceções para evitar entradas inválidas.

---

## 📚 Tecnologias Utilizadas

- **Java SE Development Kit (JDK)**
- **Bibliotecas Java** (`java.util`, `java.time`, `java.text`)

---

## 🔧 Como Executar

Certifique-se de ter um compilador de Java instalado em seu sistema (como Eclipse IDE ou NetBeans IDE.
Clone este repositório ou faça o download do código fonte.
Abra o terminal e navegue até o diretório do projeto.
Execute o programa.

# 📌 Fluxo de Operações

Ao executar o programa, você verá um menu com as opções abaixo:

```
Seja bem vindo(a) Nome Sobrenome
O que deseja fazer?
1: Consulta de Saldo 
2: Depositar 
3: Sacar 
4: Histórico de Transações 
5: Sair do sistema
```
Basta escolher a operação desejada e seguir as instruções.

## 🎯 Exemplo de Uso

### 🔹 Cadastro de Usuário:

```
Digite seu nome: Nome
Digite seu sobrenome: Sobrenome
Digite seu CPF: 123.456.789-00
```

### 🔹 Consulta de Saldo:

```
Seu saldo é de: R$ 0,00
```

### 🔹 Depósito:

```
Digite o valor de depósito: 500
Seu novo saldo é de: R$ 500,00
```

### 🔹 Saque:

```
Digite o valor de saque: 200
Seu novo saldo é de: R$ 300,00
```

### 🔹 Histórico de Transações:

```
14-03-2025 15:10:06 Ação: Consulta de Saldo
14-03-2025 15:10:10 Ação: Deposito de R$500,00
14-03-2025 15:10:22 Ação: Saque de R$200,00
```

### 🔹 Sair do sistema:

```
Obrigado por utilizar nosso banco.
```
