esse arquivo responderá as questões 4 e 12
>- "//" - comentários
>- "algoritmo" - nome do programa
>- "var" - declaração de variável
>- "inicio" - código
>- "fimalgoritmo" - fim do código
>- "+" comando usado para soma
>- ":=" outro recurso usado para resultado ou = (igual)
>- "=" condição de igual

    Algoritmo "arquivo 4"
    //este programa inclui as questões 4 e 12 do exercício de algoritmos

    //4)desenvolva um programa que leia dois números inteiros e some eles
    //12)crie um programa que detecte se o número é par ou ímpar

    Var
    a, b, c: inteiro

    Inicio
    escreval("Olá, digite o valor do primeiro número desta soma")
    leia(a)
    escreval("agora digite o segundo número a ser somado")
    leia(b)
    c:=a+b  //MOD é o comando para operador de módulo, o resto da divisão inteira.
       se c mod 2 = 0 entao//nesse caso, quando for igual a zero dividido por dois
          escreval("a soma entre ", a," e ",b ," é igual a: ", c,". Um número par")
                senao     //ele será considerado como um número par
                  escreval("a soma entre ", a," e ",b ," é igual a: ", c,". Um número ímpar")
                          //caso contrário, será considerado ímpar
    fimse

    Fimalgoritmo
