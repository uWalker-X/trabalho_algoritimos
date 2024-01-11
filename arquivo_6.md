esse arquivo irá responder a questão 10
>- "//" - comentário
>- "algoritmo" - nome do programa
>- "var" - declaração de variável
>- "inicio" - código
>- "fimalgoritmo" - fim do código
>- "*" - usado para multiplicação
>- "/" - usado para divisão
>- ":=" - usado para resultado ou = (igual)

    Algoritmo "arquivo 6"

    //10)escreva um algoritmo que leia a largura e a altura de uma parede, calcule e mostre a área a ser pintada e a quantidade de tinta necessária(2 metros de parede para cada litro de tinta).



    Var
    altura, largura, area, litro: real


    Inicio
    escreval("digite a altura da parede em metros: ")
    leia(altura)
    escreval("digite a largura da parede em metros: ")
    leia(largura)
    area:=largura*altura  //formula para descobrir a valor de uma área [A = X.Y]
    litro:=area/2         //formula para '2m² de parede para cada litro de tinta' [x= a÷2]
    escreval("seria necessário ", litro," litros de tinta para uma área de ", area, " metros.")



    Fimalgoritmo
