
# Case in Group

1.  Encontre o maior número em uma lista: Desenvolva um algoritmo para encontrar o maior número em uma lista de valores. 
- Entrada: [5, 2, 9, 1, 6, 4]
- Saída: [9]
---

2.  Encontre o menor número em uma lista: Desenvolva um algoritmo para encontrar o menor número em uma lista de valores.
- Entrada: [5, 2, 9, 1, 6, 4]
- Saída: [1]
---

3.  Verifique se um número é par ou ímpar: Escreva um algoritmo que determine se um número é par ou ímpar.
- Entrada1: 9
- Entrada2: 10
- Saída1: 9 ímpar.
- Saída2: 10 é par.
---

4.  Inverta uma string: Escreva um algoritmo que inverta uma string fornecida como entrada.
- Entrada: "Hello World!"
- Saída: "!dlroW olleH"
---

5.  Calcule o fatorial de um número: Escreva um algoritimo que calcule o fatorial de um número dado.
- Entrada: 10
- Saída: 3628800
---

6.  Verifique se uma palavra é um palíndromo: Escreva um algoritimo que identifique se uma palavra é um palíndromo.
- Entrada: "RADAR"
- Saída: "RADAR é um palíndromo."
---

7.  Converta um número decimal para binário: Implemente um algoritmo que converta um número decimal para seu equivalente em binário.
- Entrada: 25
- Saída: O número binário equivalente de 25 é: 11001
---

8.  Verifique se dois conjuntos são iguais: Desenvolva um algoritmo para verificar se dois conjuntos possuem os mesmos elementos.
- Entrada1: [1, 2, 3, 4, 5]
- Entrada2: [5, 4, 3, 2, 1]
- Saída: Os conjuntos são iguais.
---

9.  Leia o salário de um funcionário. Calcule e imprima o valor do novo salário, sabendo que ele recebeu um aumento de 25%.
- Entrada: 1000.0
- Saída: 1250.0
---

10. Sequência de Fibonacci: Escreva um algoritmo que gere os primeiros `n` números da sequência de Fibonacci.
- Entrada: 10
- Saída: Os primeiros 10 números da sequência de Fibonacci são: 0 1 1 2 3 5 8 13 21 34 
---


# Exemplos

````java
public class Main {
    public static void main(String[] args) {

        int[] arrayNumbers = {5, 2, 9, 1, 6, 4};

        int oddOrEvenValue = 9;
        String reverseStr = "Hello World!";
        int fatorial = 10;
        String palindromo = "RADAR";
        int decimalValue = 25;
        int[] array1 = {1, 2, 3, 4, 5};
        int[] array2 = {5, 4, 3, 2, 1};
        float salary = 5000.0f;
        int fibonacci = 10;

        System.out.println("--------------------------------------------------");
        System.out.println("1. Encontre o maior número em uma lista: Desenvolva um algorítimo para encontrar o\n maior número em uma lista de valores.");
        System.out.println("Entrada : " + Arrays.toString(arrayNumbers));
        System.out.println("Saída: O maior número na lista é: " + Logic.findLargestNumber(arrayNumbers));
        System.out.println("--------------------------------------------------");

        System.out.println("2. Encontre o menor número em uma lista: Desenvolva um algorítimo para encontrar o\n menor número em uma lista de valores.");
        System.out.println("Entrada : " + Arrays.toString(arrayNumbers));
        System.out.println("Saída: O menor número na lista é: " + Logic.findMinNumber(arrayNumbers));
        System.out.println("--------------------------------------------------");

        System.out.println("3. Verifique se um número é par ou ímpar: Escreva um algorítimo que determine se um\n número é par ou ímpar.");
        System.out.println("Entrada: " + oddOrEvenValue);
        System.out.println("Saída: " + Logic.oddOrEven(oddOrEvenValue));
        System.out.println("--------------------------------------------------");

        System.out.println("4. Inverta uma string: Escreva um algorítimo que inverta uma string fornecida como\n entrada.");
        System.out.println("Entrada: " + reverseStr);
        System.out.println("Saída: " + Logic.reverseString(reverseStr));
        System.out.println("--------------------------------------------------");

        System.out.println("5. Calcule o fatorial de um número: Escreva um algoritimo que calcule o fatorial de um\n número dado.");
        System.out.println("Entrada: " + fatorial);
        System.out.println("Saída: " + Logic.calculateFactorial(fatorial));
        System.out.println("--------------------------------------------------");

        System.out.println("6. Verifique se uma palavra é um palíndromo: Escreva um algoritimo que identifique se\n uma palavra é um palíndromo.");
        System.out.println("Entrada: " + palindromo);
        System.out.println("Saída: "+ Logic.isPalindrome(palindromo));
        System.out.println("--------------------------------------------------");

        System.out.println("7. Converta um número decimal para binário: Implemente um algorítimo que converta um\n número decimal para seu equivalente em binário.");
        System.out.println("Entrada: " + decimalValue);
        System.out.println("Saída: O número binário equivalente de "+decimalValue+" é: " + Logic.decimalToBinary(decimalValue) );
        System.out.println("--------------------------------------------------");


        System.out.println("8. Verifique se dois conjuntos são iguais: Desenvolva um algorítimo para verificar se\n dois conjuntos possuem os mesmos elementos.");
        System.out.println("Entrada1: " + Arrays.toString(array1));
        System.out.println("Entrada2: " + Arrays.toString(array2));
        System.out.println("Saída: " + Logic.areArraysEqual(array1, array2));
        System.out.println("--------------------------------------------------");


        System.out.println("9. Leia o salário de um funcionário. Calcule e imprima o valor do novo salário,\n sabendo que ele recebeu um aumento de 25%.");
        System.out.println("Entrada: " + salary);
        System.out.println("Saída: " + Logic.salaryCalc(salary));
        System.out.println("--------------------------------------------------");

        System.out.println("10. Sequência de Fibonacci: Escreva um algorítimo que gere os primeiros `n` números\n da sequência de Fibonacci.");
        System.out.println("Entrada: 10");
        System.out.println("Saída: Os primeiros "+fibonacci+" números da sequência de Fibonacci são: " + Logic.fibonacciCalc(fibonacci));
        System.out.println("--------------------------------------------------");
    }
}
````
# Console
```xsdregexp
--------------------------------------------------
1. Encontre o maior número em uma lista: Desenvolva um algorítimo para encontrar o
 maior número em uma lista de valores.
Entrada : [5, 2, 9, 1, 6, 4]
Saída: O maior número na lista é: 9
--------------------------------------------------
2. Encontre o menor número em uma lista: Desenvolva um algorítimo para encontrar o
 menor número em uma lista de valores.
Entrada : [5, 2, 9, 1, 6, 4]
Saída: O menor número na lista é: 1
--------------------------------------------------
3. Verifique se um número é par ou ímpar: Escreva um algorítimo que determine se um
 número é par ou ímpar.
Entrada: 9
Saída: 9 é ímpar.
--------------------------------------------------
4. Inverta uma string: Escreva um algorítimo que inverta uma string fornecida como
 entrada.
Entrada: Hello World!
Saída: !dlroW olleH
--------------------------------------------------
5. Calcule o fatorial de um número: Escreva um algoritimo que calcule o fatorial de um
 número dado.
Entrada: 10
Saída: 3628800
--------------------------------------------------
6. Verifique se uma palavra é um palíndromo: Escreva um algoritimo que identifique se
 uma palavra é um palíndromo.
Entrada: RADAR
Saída: RADAR é um palíndromo.
--------------------------------------------------
7. Converta um número decimal para binário: Implemente um algorítimo que converta um
 número decimal para seu equivalente em binário.
Entrada: 25
Saída: O número binário equivalente de 25 é: O número binário equivalente de 25 é: 11001
--------------------------------------------------
8. Verifique se dois conjuntos são iguais: Desenvolva um algorítimo para verificar se
 dois conjuntos possuem os mesmos elementos.
Entrada1: [1, 2, 3, 4, 5]
Entrada2: [5, 4, 3, 2, 1]
Saída: Os conjuntos são iguais.
--------------------------------------------------
9. Leia o salário de um funcionário. Calcule e imprima o valor do novo salário,
 sabendo que ele recebeu um aumento de 0.25%.
Entrada: 5000.0
Saída: 6250.0
--------------------------------------------------
10. Sequência de Fibonacci: Escreva um algorítimo que gere os primeiros `n` números
 da sequência de Fibonacci.
Entrada: 10
Os primeiros 10 números da sequência de Fibonacci são:
Saída: Os primeiros 10 números da sequência de Fibonacci são: 0 1 1 2 3 5 8 13 21 34
--------------------------------------------------
```
