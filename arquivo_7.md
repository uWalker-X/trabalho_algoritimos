o arquivo 7 irá responder a questão 11
>- "//" - comentário
>- "algoritmo" - nome do arquivo
>- "inicio" - código
>- "fimalgoritmo" - fim do código
>- "<=" - menor ou igual que:
>- ":=" - comando usado para resultado ou = (igual)
>- "-" - comando usado para subtração
>- "*" - comando usado para multiplicação

    Algoritmo "show me your smile"
    //11)escreva um  algoritmo que pergunte a velocidade de um carro, e aplique uma multa caso ele ultrapasse a velocidade de 80km/h, cobrando R$5 pra cada km acima do limite


    Var
    km, multa: real


    Inicio
    escreval("digite a velocidade do carro em km/h: ")
    leia(km)
    se km <= 80 entao //comando SE usado para definir desvios de condicionais
       escreval("seu carro estava dentro do limite de velocidade")
       //ENTAO executa o comando SE que corresponde a uma condicional verdadeira
    senao            //SENAO coresponde a uma condicional falsa
    multa:=(km-80)*5 //podem haver mais de duas, basta usar o comando SENAO SE
         escreval("seu carro ultrapassou o limite de velocidade")
         escreval("a multa para cada km/h ultrapassado é de ", multa," reais.")
    fimse      //FIMSE fecha o laço SE
    //porém, deve haver um FIMSE para cada laço SE criado


    Fimalgoritmo
