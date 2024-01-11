o arquivo 9 responderá as questões 14, 15, 16, 17, 18, 19, 20, 22, e 23
>- "//" - comentário
>- "algoritmo" - nome do arquivo
>- "inicio" - código
>- "fimalgoritmo" - fim do código
>- "+" - comando usado para adição
>- "-" - comando usado para subtração
>- ">" - sinal de maior
>- ">=" - maior ou igual que
>- "<" - sinal de menor
>- ":=" - comando usado para resultado ou = (igual)
>- "<=" - menor ou igual que

    Algoritmo "arquivo 9"
    
    //esse algoritmo inclui as questões 14, 15, 16, 17, 18, 19, 20, 22 e 23
    
    //14) escreva um programa que mostre na tela a contagem
    //                6 7 8 9 10 11 Acabou!
    
    //15) escreva um programa que mostre na tela a contagem
    //              10 9 8 7 6 5 4 3 Acabou!
    
    //16) escreva um programa que mostre na tela a contagem
    //              0 3 6 9 12 15 18 Acabou!
    
    //17)escreva um programa que mostre na tela a contagem
    //            100 95 90 85 ... 5 0 Acabou!
    
    //18)escreva um programa que conte até o número digitado pelo usuário
    
    //19)escreva um programa que mostre uma contagem de 30 a 1, mostrando os números divisiveis por 4
    
    //20)crie um programa que mostre na tela a contagem(usando "faça enquanto")
    //         0 3 6 9 12 15 18 21 24 27 30 Acabou!
    
    //22)crie um programa que mostre na tela a contagem(usando "para")
    //           0 5 10 15 20 25 30 35 40 Acabou!
    
    //23)crie um programa que mostre na tela a contagem(usando "para")
    //       100 90 80 70 60 50 40 30 20 10 0 Acabou!
    
    
    Var
    contador, numero: inteiro
    
    Inicio
    escreval("14)")
    escreval("         contador progressivo       ")   //14)
    contador:=6
    repita
    escreval(contador)
    contador:=contador+1
    ate(contador>11)
    escreval("contagem finalizada")
    
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("15)")
    escreval("         contador regressivo        ")   //15)
    contador:=10
    repita
    escreval(contador)
    contador:=contador-1
    ate(contador<3)
    escreval("contagem finalizada")
    
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("16)")
    escreval("   contador progressivo de base 3   ")   //16)
    contador:=0
    repita
    escreval(contador)
    contador:=contador+3
    ate(contador>18)
    escreval("contagem finalizada")
    
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("17)")
    escreval("   contador regressivo de base 5   ")    //17)
    contador:=100
    repita
    escreval(contador)
    contador:=contador-5
    ate(contador<0)
    escreval("contagem finalizada")
    
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("19)")
    escreval("   marcador de divisíveis por 4   ")     //19)
    contador:=30
    enquanto (contador >= 1) faca
      escreval(contador)
      contador:=contador-1
          se (contador mod 4 = 0) entao
          escreval("[", contador, "]")
          fimse
      fimenquanto
      
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("20)")
    escreval(" contador de base 3(faça enquanto)")     //20)
    contador:=0
        enquanto (contador <= 30) faca
        escreval (contador)
        contador:=contador+3
        fimenquanto
        
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("22)")
    escreval(" contador de base 5(comando para)")      //22)
    contador:=0
       para contador de 0 ate 40 passo 5 faca
         escreval(contador)
       fimpara
    
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("23)")
    escreval(" contador de base 10(comando para)")     //23)
    contador:=100
      para contador de 100 ate 0 passo -10 faca
      escreval(contador)
      fimpara
    
    escreval()
    escreval("_________________________________________")
    escreval()
    
    escreval("18)")                                    //18)
    escreval("esses são alguns exemplos de 'contadores' criados no VisualG")
    escreval("agora digite um número inteiro positivo para iniciarmos a última contagem")
    leia(numero)
    escreval("entendido!")
                para contador de 0 ate numero passo 1 faca
                escreval(contador)
                fimpara
    escreval("contagem finalizada")
    
    Fimalgoritmo
