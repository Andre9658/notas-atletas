#Projeto Notas dos Atletas#

Este projeto foi desenvolvido para calcular a média das notas de atletas em uma competição de ginástica artística.



#Objetivo#

--Criar uma aplicação em JavaScriptcapaz de:

- Receber o nome e as cinco notas de cada atleta;
- **Descartar a maior e a menor nota;
- Calcular a média das três notas restantes;
- Exibir o nome do atleta, as notas e a média válida.



#Regras da Competição#

1- Cada atleta recebe 5 notas (de 1 a 10);
2- A maior e a menor nota são desconsideradas;


#Exemplo de Entrada#

#javascript

let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas:  [8, 10, 10, 7, 9.33]
 },
 {
   nome: "Daiane Jelinsky",
   notas: [7, 10, 9.5, 9.5, 8]
 },
 {
   nome: "Bruno Castro",
   notas: [10, 10, 10, 9, 9.5]
 }
];

