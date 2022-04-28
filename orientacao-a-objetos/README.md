# Orientação a Objetos

Este repositório contém a atividade prática do Curso "Orientação a Objetos", que faz parte do Basecamp de Javascript da [Digital Innovation One](https://digitalinnovation.one/).

## Atividade: Conta Bancária

Nesta atividade, testei os conceitos de Orientação a Objetos simulando a criação de diversos tipos de contas bancárias e operações disponíveis em cada uma.

1. Criei a classe `ContaBancaria`, que possui os parâmetros `agencia`, `numero`, `tipo` e `saldo`;
2. Dentro de `ContaBancaria`, construi o getter e o setter de `saldo`;
3. Dentro de `ContaBancaria`, criei os métodos `sacar` e `depositar`;
4. Criei uma classe-filha chamada `ContaCorrente` que herda todos esses parâmetros e ainda possui o parâmetro `cartaoCredito`;
5. Ainda em `ContaCorrente`, construi o getter e o setter de `cartaoCredito`;
6. Ainda em `ContaCorrente`, fiz com que o `tipo` seja 'conta corrente' por padrão;
7. Criei uma classe-filha chamada `ContaPoupanca` que herda todos os parâmetros de `ContaBancaria`;
8. Criei uma classe-filha chamada `ContaUniversitaria` que herda todos os parâmetros de `ContaBancaria`;
9. Fiz com que o método `saque` de `ContaUniversitaria` apenas seja capaz de sacar valores **menores que 500 reais**.
