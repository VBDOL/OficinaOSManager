# Sistema de Controle de Oficina Mecânica

![Adicione aqui a imagem do esquema conceitual](/sqlmy.png)

## Contexto do Projeto
Este projeto foi desenvolvido com o objetivo de criar um esquema conceitual para um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica. O sistema abrange desde o cadastro de clientes e veículos até a execução de serviços e o controle de peças e mão de obra.

## Objetivo
Desenvolver um esquema conceitual que represente todas as entidades, relacionamentos e atributos descritos na narrativa, com base no contexto de funcionamento de uma oficina mecânica.

## Descrição do Esquema Conceitual
O esquema conceitual foi projetado com as seguintes entidades principais:

- **Cliente**: Representa os clientes da oficina, com atributos como código, nome, endereço e telefone.
- **Veículo**: Detalha os veículos trazidos pelos clientes, incluindo placa, modelo, marca e ano.
- **Mecânico**: Representa os profissionais que realizam os serviços, com atributos como código, nome, endereço e especialidade.
- **Equipe**: Agrupa os mecânicos em equipes responsáveis por serviços específicos.
- **Ordem de Serviço (OS)**: Centraliza informações sobre os serviços realizados, como número, data de emissão, status, valor total e datas importantes.
- **Serviço**: Detalha os serviços executados, vinculados às ordens de serviço.
- **Peça**: Lista as peças utilizadas, também vinculadas às ordens de serviço.

## Relacionamentos
- Um **Cliente** pode possuir múltiplos **Veículos**.
- Um **Veículo** pode ter várias **Ordens de Serviço (OS)**.
- Uma **Ordem de Serviço (OS)** pode conter múltiplos **Serviços** e **Peças**.
- Uma **Ordem de Serviço (OS)** é atribuída a uma **Equipe**.
- Uma **Equipe** é composta por múltiplos **Mecânicos**.

## Estrutura do Repositório
- `README.md`: Este arquivo, explicando o contexto e as decisões de design do esquema.
- `diagram.png` (ou outro formato): Arquivo contendo o diagrama de Entidade-Relacionamento (ER) representando o esquema conceitual.
- `documentacao/`: Pasta com descrições detalhadas das entidades e relacionamentos.

## Observação

Alguns detalhes foram inferidos para complementar a narrativa fornecida. Caso tenha sugestões ou correções, sinta-se à vontade para contribuir.

---

