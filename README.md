
# 💻 Resolução desafio vaga de estágio - Target Sistemas

1) O resultado da soma é 91;
2) 
```
 function isFibonacciNumber(num) {
    // Função para verificar se um número é um quadrado perfeito
    function isPerfectSquare(x) {
        const sqrt = Math.sqrt(x);
        return sqrt * sqrt === x;
    }

    // Função para verificar se um número está na sequência de Fibonacci
    function isFibonacci(n) {
        return isPerfectSquare(5 * n * n + 4) || isPerfectSquare(5 * n * n - 4);
    }

    if (num < 0) {
        return "O número deve ser não-negativo.";
    }

    if (isFibonacci(num)) {
        return `${num} pertence à sequência de Fibonacci.`;
    } else {
        return `${num} não pertence à sequência de Fibonacci.`;
    }
}

// Exemplo de uso
const numeroInformado = 13; // Substitua pelo número desejado
const resultado = isFibonacciNumber(numeroInformado);
console.log(resultado);

```
3) 9, 128, 36, 64, 13, 27;

4) Na primeira ida, ligaria o primeiro interruptor e esperaria alguns minutos, desligaria o primeiro interruptor e ligaria o segundo e entraria na sala com as lâmpadas. Na segunda ida, observaria a lâmpada que está acesa, se a lâmpada está acesa, então o interruptor ligado na primeira ida controla a lâmpada, se a lâmpada está apagada e ainda estiver quente, então o interruptor ligado na segunda ida controla a lâmpada e se a lâmpada estiver apagada e fria, então o interruptor que não foi tocado controla a lâmpada;

5) 
```
function inverterString(str) {
    let resultado = '';
    
    // Itera sobre os caracteres da string de trás para frente
    for (let i = str.length - 1; i >= 0; i--) {
        resultado += str[i];
    }

    return resultado;
}

// Exemplo de uso
const minhaString = 'Olá, Mundo!'; // Substitua pela string desejado
const stringInvertida = inverterString(minhaString);
console.log(stringInvertida);

```


