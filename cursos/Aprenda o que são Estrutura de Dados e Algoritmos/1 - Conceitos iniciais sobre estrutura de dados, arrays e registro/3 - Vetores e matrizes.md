# Vetores e matrizes

---

## Definição

Também chamadas de Arrays, vetores e matrizes são estruturas simples que agrupam múltiplas variáveis do mesmo tipo numa espécie de lista.

## Vetor

Vetor ou array uni-dimensional é uma estrutura que armazena múltiplas variáveis do mesmo tipo. Esta estrutura é indexada, isto é, seus itens são acessados por meio da posição em que ele está inserido.

Os índices não começam no 1, começam no 0. Logo, a primeira posição de um vetor é 0, a segunda é 1, a terceira é 2 e assim por diante.

### Exemplo

```typescript
// Criamos um vetor de números, ume espécie de lista de números.
// Dentro dessa "lista" temos os números 39, 45, 54 e 55.
const vetor: number[] = [39, 45, 54, 55]

// O primeiro item do array é o 39.
// Para acessar o valor do primeiro item do array, usamos.
console.log(vetor[0])
// => 39

// Nos demais casos:
console.log(vetor[1])
// => 45

console.log(vetor[2])
// => 54

console.log(vetor[3])
// => 55

// Índices: | 0  | 1  | 2  | 3  |
// Valores: | 39 | 45 | 54 | 55 |
```

## Matriz

Uma matriz ou array multi-dimensional é um vetor de vetores.

Ou seja, em vez de uma "lista de números" temos uma "lista com várias listas de números dentro".

### Exemplo

```typescript
// Criamos um vetor "matriz" em que o tipo de dado que ele armazena são vetores de números.
// Dentro dessa "lista de listas" temos duas "listas".
// A primeira contém os números 1 e 2.
// A segunda contém os números 3 e 4.
const matriz: number[][] = [
    [1, 2],
    [3, 4]
]

// Se pegarmos o primeiro item da matriz, temos o primeiro vetor.
console.log(matriz[0])
// => [1, 2]

// Logo, podemos pegar o segundo item do primeito vetor assim:
console.log(matriz[0][1])
// => 2
```

