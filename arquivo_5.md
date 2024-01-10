esse arquivo irá responder a questão 10
>- "//" - comentário
>- "algoritmo" - nome do programa
>- "var" - declaração de variável
>- "inicio" - código
>- "fimalgoritmo" - fim do código
>- "/" - usado para divisão
>- "*" - usado para multiplicação
>- ":=" - usado para resultado ou = (igual)

    Algoritmo "arquivo 5"
    //crie um programa que leia a distância em metros e mostre em outras unidades de medida


    Var
    km, hm, dam, m, dm, cm, mm: real



    Inicio
    escreval("digite uma distância em metros: ")
    leia(m)
    km:= m/1000
    hm:= m/100
    dam:=m/10

    dm:=m* 10
    cm:=m* 100
    mm:=m* 1000
    escreval("a distânia ", m,"m em outras unidades de medida corresponde a:")
    escreval(km," km")
    escreval(hm," hm")
    escreval(dam,"dam")
    escreval()
    escreval(dm," dm")
    escreval(cm," cm")
    escreval(mm," mm")

    Fimalgoritmo
