# Lógica de Programação Utilizando Javascript.

#### Exercícios concedidos pelo Alura.

1) Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```let contador = 1;
while (contador <= 10) {
    console.log(contador);
    contador++;
}
```
2) Crie um contador que começa em 10 e vá até 0 usando um loop while.Mostre cada número.

```let contador = 10;

while (contador >= 0) {
    console.log(contador);
    contador--;
}
  ``` 


3) Crie um programa de contagem regressiva.Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```let contagem = prompt("Digite o número para contagem regressiva");

while (contagem >= 0){
    console.log(contagem);
    contagem--;
}
```

4) Crie um programa de contagem progressiva.Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```let numeroMax = prompt("Digite o número para contagem regressiva");
let contagem = 0;

while (contagem <= numeroMax){
    console.log(contagem);
    contagem++;
}
```
Desafios finais

1) Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.
```
console.log("Boas vindas ao primeiro Hello World, programadora!")
```

2) Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.
```
var name = 'Mari';
console.log(`Olá, ${name}`);
```

3) Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" .
```
var name = 'Mari';
alert(`Olá, ${name}`);
```

4) Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.
```
var respostaUser = prompt("Qual linguagem de programação você mais gosta?");
console.log(respostaUser)
```

5) Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.
```
var valorUm = 5;
var valorDois = 3;
var resultado = valorUm + valorDois;
console.log(`A soma entre ${valorUm} e ${valorDois} é de ${resultado}`)
```

7) Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.
```
var valorUm = 5;
var valorDois = 3;
var resultado = valorUm + valorDois;
console.log(`A diferença entre ${valorUm} e ${valorDois} é de ${resultado}`)
```

9) Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

```
var idade = prompt("Digite sua idade")
if(idade > 18){
console.log("Maior de idade")
}
else{
console.log("Menor de idade")
}
```

11) Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.

12) Use um loop while para imprimir os números de 1 a 10 no console.

13) Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

14) Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.

15) Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.

16) Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.
