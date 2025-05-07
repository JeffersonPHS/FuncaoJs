# Tipos de Funções


# Função Declarativa

## Descrição
A declaração de função é definida com a palavra-chave function, juntamente com um nome único. Em seguida, vêm os parênteses (), o bloco {} e as instruções dentro desse bloco.

## Exemplos

```javascript
// Ex 1
function inicio() {
  console.log("Começando...")
}
inicio()

// Ex 2
function total() {
  console.log("Calculando total...")
}
total()

// Ex 3
function senha() {
  console.log("Verificando senha...")
}
senha()
```
## Vantagem
- Permite chamar antes da declaração da função por causa do hoisting.
## Desvantagem
- Não permite atribuição diretamente na variável.



# Função Expressiva

## Descrição 

A expressão de função se difere de uma declaração de função normal na forma a qual declaramos o nome. 

## Exemplos

```javascript
//Ex1
let atecao = function() {
 console.log("olá");
}
atecao()
//Ex2
let inicio = function() {
console.log(iniciando...)
}
inicio()
//Ex3
let calcular = function (x, y) {
return x + y;
}
console.log (`sua soma: ${calcular(4, 3)}`)
```

## Vantagem
 - Diferente da função declarativa a expressiva permite atribuir diretamente na variável. 

## Desvantagem
- Não permite chamar antes da declaração da função, ou seja, não permite hoisting.

# Função Arrow 
## Descrição 
Permite criar funções anônimas atribuída a variáveis definida com uma seta "=>".

## Exemplos 

```javascript
//Ex1 
let nome = ( ) => console.log ("Jefferson");
nome( );
//Ex2
let total = ( ) => console.log ("teste");
total( )
//Ex3
let soma = x => x+ x;
console.log (`Seu valor: ${soma(5)}`)
````
## Vantagem
- A sintaxe é enxuta e fácil de entender.
## Desvantagem
- Não possui hoisting, ou seja, não permite executar antes da declaração da Função.
