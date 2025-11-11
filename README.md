# Curr-culo-RenanSantana-3C

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <style>
        h1 {
            color: blue;
            font-size: 18px;
        }
        h2 {
            color: red;
            font-size: 18px;
        }
    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Olá, mundo</h1>
    <h2>Olá, mundo</h2>
    <h3>Olá. mundo</h3>
    <h4>Olá, mundo</h4>
    <h5>Olá, mundo</h5>
    <h6>Olá, mundo</h6>

<h1 id="titulo">Oi!</h1>
<button onclick="mudar()">Clique</button>
</body>
<script>
console.log("Olá,mundo");

let nome = "Saturn";
console.log("Nome: ", nome); // Saída: Nome: Saturno

let número = 25;
console.log("Número: ", número);

let idade2 = parseInt(prompt("Insira sua idade: "));
if (idade >=18){
    console.log("Maior de Idade");
}else{
    console.log("Menor de Idade");
}

for (let i = 1; i<= 3; i++) {
    console.log("Número: " + i);
}

function mudar() {
    document.getElementById("titulo").innerText = "texto alterado!";
}

let frutas = ["Maçã", "Banana", "Laranja"];
console.log("Frutas:", frutas);
console.log("Primeira fruta:", frutas[0]);

let a = 10;
let b = 5;

console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);


</script>
</html>
