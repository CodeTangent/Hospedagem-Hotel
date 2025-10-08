# Sistema de Hospedagem em C#

## Visão Geral
O sistema permite registrar hóspedes, gerenciar suítes e calcular reservas automaticamente, incluindo validação de capacidade e descontos progressivos em estadias longas.

Esse projeto foi desenvolvido como parte de um desafio guiado do curso da DIO em C#.


## Estrutura do Projeto

HospedagemHotel/
├── Models/
│   ├── Pessoa.cs
│   ├── Suite.cs
│   └── Reserva.cs
├── Program.cs
└── README.md


## Funcionalidades Principais

* Cadastro de Hóspedes (classe Pessoa)

* Cadastro de Suítes (classe Suite, com tipo e capacidade)

* Reserva de Quartos (classe Reserva, integrando hóspedes e suíte)

* Cálculo Automático do Valor da Diária

* Desconto de 10% para reservas ≥ 10 dias

* Validação de Capacidade

* Impede reservas com número de hóspedes superior à capacidade da suíte

* Métodos para Obter Quantidade de Hóspedes e Valor Total


## Conceitos Aplicados

* Programação Orientada a Objetos (POO)

* Encapsulamento e abstração de classes

* Validação de dados e tratamento de exceções

* Boas práticas de nomeação e estrutura de código
