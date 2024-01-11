o arquivo 8 irá responder a questão 21
>- "//" comentário
>- "algoritmo" - nome do arquivo
>- "var" - declaração de variável
>- "inicio" - código
>- "fimalgoritmo" - fim do código
>- "+" - comando usado para adição
>- ":=" - comando usado para resultado ou = (igual)

    Algoritmo "arquivo 8"
    //21)faça um programa usando a estrutura 'faça enquanto' que leia a idade
    Var
    idade, contador, maiorq, total, soma, op : inteiro
    media: real


    Inicio
    contador:=1


    escreva("Olá! ")
      escreval("Digite a idade do ", contador,"° usuário")
      leia(idade)
  
       repita
       escreval("deseja adicionar mais algum usúarios?")
       escreval("1: não")
       escreval("2: sim")
       leia(op)
          contador:=1+contador
       escolha(op)
       caso 1
       escreval("finalizando programa")
       caso 2
       escreval("digite o número do ", contador,"º usuário")
       leia(op)
      ate(op)=1
  
    Fimalgoritmo
