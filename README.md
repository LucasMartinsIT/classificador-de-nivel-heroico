# Classificador de Nível de Herói

Este projeto serve para classificar o nível de um herói com base na quantidade de experiência (XP) que ele possui.

## Tecnologias

- JavaScript

## Como Usar

1. Abra o console do desenvolvedor no seu navegador (F12).
2. Copie e cole o código JavaScript do projeto.
3. Execute o código.
4. Quando solicitado, insira o nome do herói e a quantidade de XP.
5. O nível do herói será exibido no console.

## Exemplo

Aqui está um exemplo de uso da função:

```javascript
// Chame a função passando o nome e a quantidade de XP
const nomeHeroi = prompt("Digite o nome do herói:");
const xpHeroi = parseInt(prompt("Digite a quantidade de experiência (XP) do herói:"), 10);
classificarHeroi(nomeHeroi, xpHeroi);
