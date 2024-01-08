com o objetivo de diminuir a quantidade de arquivos, alguns deles responderão mais de uma questão

- nosso primeiro arquivo terá como foco responder as questões 1,2,3, 9 e 13
> o primeiro arquivo além responder 5 questões, adiciona um comando em loop na questão 13, que será melhor desenvolvido no arquivo

> indentificando alguns sinônimos:
>- "Algoritmo" - nome do arquivo
>- "//" - comentário
>- "Var" - declaração de variável
>- "'Inicio" - código
>- "Fimalgoritmo" - fim do código

    Algoritmo "arquivo_1"
    //este algoritmo inclui as questões 1, 2, 3 e 9 do exercício de algoritimos

    //1)escreva um programa que mostre na tela a mensagem "Olá mundo!"
    //2)faça um programa que dê boas vindas e leia o nome da pessoa que interagir
    //3)Crie um programa que leia o nome e o salário dessa pessoa
    //9)converta o dinheiro de real para dólar, usando como referência $1.00=R$3.45
    //13)crie um programa que mostre a situação do usuario em relação ao alistamento  militar

    Var
    salario, r, ano, alistamento, al: real
    op, tcl: inteiro
    nome: caractere

    Inicio
    //a seguir serão respondidas as questões 1 e 2 respectivamentes
    //o uso do comando "escreva" seguido por parêntese e aspas permite que exiba a mensagem
    escreval("Olá mundo")
    escreva("Olá, voçê! ")
    escreva("Qual seu nome? ")
    leia(nome)    //o comando leia aguardará você inserir a variável correspondente
    escreval("Olá, ", nome, ", seja bem vindo!")
    escreval()
    //a seguir se inicia a questão 13
    escreval("em que ano você nascel?")
    leia(ano)
    alistamento:=(ano-2022)+18
    al:=alistamento*-1  
    se(alistamento<0) entao   //o comando "se" organizará melhor as repostas situacionais
    escreval("se passaram ", al, " anos do seu alistamento militar")
      senao                   //a variavel "al" tem o único propósito de manter os números positivos
      se(alistamento=0) entao
      escreval("está no ano de você se alistar!")
        senao
          se(alistamento>0) entao
          escreval("ainda faltam ", alistamento," anos pro seu alistamento")
          fimse
        fimse
      fimse
    escreval()
    //a seguir se inicia respectivamente as questões 3 e 9
    escreval("escolha dentre as duas opções abaixo")
    repita
    escreval("você posui um emprego?")
    escreval("1: não")
    escreval("2: sim")
        leia(op)     //a variavel "op" de 'opção' tem a finalidade de ler as opções oferecidas pelo programa
          escolha(op)//neste caso são duas
          caso 1
          escreva("ok, esse algoritmo chegou ai fim.")
          caso 2
          escreval("Ótimo, digite seu salário")
          leia(salario)
          escreval("o salário do funcionário ", nome, " é de ",salario)
          r:=salario/3.45
          escreval()   //9)
          escreval("seu salário em dólares seria de aproximadamente:")
          escreval("$", r, " em uma conversão direta")
          escreval()
          escreval()
          escreval("pressione ctrl+F2 para finalizar o programa")
          escreval()
          escreval()

              outrocaso //esse comando anula qualquer outra opção que não esteja programada
              escreval("opção inválida")
          fimescolha
    leia(tcl)
    ate(op=2)

    Fimalgoritmo
