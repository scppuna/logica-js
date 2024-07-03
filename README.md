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
