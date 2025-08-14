# 💳 Sistema de Gerenciamento de Conta Bancária

Este projeto em **Java** simula a criação e gerenciamento de uma conta bancária, permitindo **depósitos, saques** e exibição de informações da conta, com tratamento para depósito inicial opcional e taxa de saque.

## 🚀 Funcionalidades

- Criar conta bancária com ou sem depósito inicial
- Realizar depósitos
- Realizar saques com taxa fixa de $5.00
- Exibir informações atualizadas da conta

## 🛠️ Tecnologias Utilizadas

- **Java 17+**
- **Orientação a Objetos (OOP)**
- **Scanner** para entrada de dados
- **Locale** para formatação numérica

## 📌 Exemplo de Execução

Enter account number: 1234

Enter account holder: Caiul Silva

Is there an initial deposit (y/n)? y

Enter initial deposit value: 500.00

Account data:
Account 1234, Holder: Caiul Silva, Balance: $ 500.00

Enter a deposit value: 200.00

Updated account data:
Account 1234, Holder: Caiul Silva, Balance: $ 700.00

Enter a withdraw value: 100.00

Updated account data:
Account 1234, Holder: Caiul Silva, Balance: $ 595.00

// pós a taxa de saque é R$ 5.00


## 📖 Conceitos Aplicados

- Encapsulamento
- Sobrecarga de construtores
- Métodos de instância (`deposit` e `withdraw`)
- Formatação monetária com `String.format`
- Interação com o usuário via terminal