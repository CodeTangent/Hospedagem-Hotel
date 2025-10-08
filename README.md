# Sistema de Hospedagem em C#

## Visão Geral
O sistema permite registrar hóspedes, gerenciar suítes e calcular reservas automaticamente, incluindo validação de capacidade e aplicação de descontos progressivos em estadias longas.

Esse projeto foi desenvolvido como parte de um desafio guiado do curso da DIO em C#.

## Funcionalidades Principais
- **Cadastro de Hóspedes** (classe `Pessoa`)
- **Cadastro de Suítes** (classe `Suite`, com tipo e capacidade)
- **Reserva de Quartos** (classe `Reserva`, integrando hóspedes e suíte)
- **Cálculo Automático do Valor da Diária**
- **Desconto de 10%** para reservas com duração igual ou superior a 10 dias
- **Validação de Capacidade**  
  Impede reservas com número de hóspedes superior à capacidade da suíte
- **Métodos de Consulta**  
  Obtenção da quantidade de hóspedes e do valor total da reserva

---

## Conceitos Aplicados
- Programação Orientada a Objetos (POO)
- Encapsulamento e abstração de classes
- Validação de dados e tratamento de exceções
- Boas práticas de nomeação e estrutura de código
