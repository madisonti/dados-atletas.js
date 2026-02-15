# dados-atletas

## Descrição do Projeto

O **dados-atletas** é uma aplicação em JavaScript que permite registrar informações de atletas, calcular parâmetros importantes como categoria, IMC e média válida das notas, e exibir essas informações de forma clara para o usuário.

A aplicação foi desenvolvida para auxiliar competições esportivas e treinamentos, automatizando cálculos e fornecendo um resumo completo de cada atleta.

## Funcionalidades

- Registrar informações do atleta: nome, idade, peso, altura e notas.
- Calcular a categoria do atleta com base na idade:
  - Infantil: 9 a 11 anos
  - Juvenil: 12 a 13 anos
  - Intermediário: 14 a 15 anos
  - Adulto: 16 a 30 anos
  - Sem categoria: demais idades
- Calcular o IMC (Índice de Massa Corporal) usando a fórmula `peso / (altura²)`.
- Calcular a média válida das notas, descartando a maior e a menor nota.
- Exibir todas as informações capturadas e calculadas de forma organizada.

## Tecnologias

- JavaScript (ES6)
- Node.js (opcional para execução no terminal)

## Estrutura do Projeto


## Como Usar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/dados-atletas.git

cd dados-atletas

node dados-atletas.js
Exemplo de Uso:
const atleta = new Atleta("Cesar Abascal", 30, 80, 1.70, [10, 9.34, 8.42, 10, 7.88]);

console.log("Nome:", atleta.obtemNomeAtleta());
console.log("Idade:", atleta.obtemIdadeAtleta());
console.log("Peso:", atleta.obtemPesoAtleta());
console.log("Altura:", atleta.obtemAlturaAtleta());
console.log("Notas:", atleta.obtemNotasAtleta());
console.log("Categoria:", atleta.obtemCategoria());
console.log("IMC:", atleta.obtemIMC());
console.log("Média válida:", atleta.obtemMediaValida());




