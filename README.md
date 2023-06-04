# portugol_basic
Portugol básico de aprendizagem e algumas atividades prontas! / Portugol Basic for learning and some ready-made activities!

# portugol_Atividades
Atividade 1 de portugol : Faça um algoritmo que receba dois números e exiba o resultado da soma.
// visualg
Algoritmo "SomaDosNumeros"

Var

  nu1,nu2,soma: real

Inicio

escreva("digite primeiro numero da soma: ")
leia(nu1)
escreva("digite segundo numero da soma: ")
leia(nu2)
soma := nu1 + nu2
escreva("resultado = ",soma)


Fimalgoritmo
====================================================================================
Atividade 2 de portugol : Faça um algoritmo que receba dois números e exiba o resultado da soma, subtração, divisão, multiplicação.
Algoritmo "SubSomaMultDiv"

Var

  nu1,nu2,resul: real

Inicio

escreva("digite primeiro numero: ")
leia(nu1)
escreva("digite segundo numero: ")
leia(nu2)
resul := nu1 + nu2
escreval("soma dos numeros: ",resul)
resul := nu1 - nu2
escreval("subtração dos numeros: ",resul)
resul := nu1 * nu2
escreval("multiplicação dos numeros: ",resul)
resul := nu1 / nu2
escreval("divisão dos numeros: ",resul)
Fimalgoritmo
====================================================================================
Atividade 3 de portugol : Faça um algoritmo para determinar o consumo medio de um automovel sendo fornecida a distancia total e o combustivel total gasto.
Algoritmo "MediaGasolina"
Algoritmo "SubSomaMultDiv"

Var

  distKm,gasGasto,media: real

Inicio

escreva("digite a distancia percorrida em Km's: ")
leia(distKm)
escreva("digite quanto de gasolisa voce consumiu: ")
leia(gasGasto)
media := distKm / gasGasto
escreva("media de combustivel gasto é de: ",media,"L")

Fimalgoritmo
====================================================================================
Atividade 4 de portugol : Faça um algoritmo que leia o nome de um vendendor, o seu salario fixo e o total de vendas no mês
sabendo que o vendedor recebe 15% de cada venda
informe seu salario fixo e o salario final.
Algoritmo "SalarioMComissao"

Var

   salarioFixo,comissao,vendas,tot: real
   quantidade,C : inteiro

   nome: caracter

Inicio

escreva("qual seu nome? : ")
leia(nome)
escreva("digite qual seu salario fixo: ")
leia(salarioFixo)
escreva("digite a quantidade de vendas que voce fez esse mês: ")
leia(quantidade)

    C := 1
   enquanto C <= quantidade faça
        escreval("digite o valor da ",c,"° venda :")
        leia(vendas)
        C:= C + 1
        tot :=  tot + vendas
   fimenquanto

tot := (tot * 0.15) + salarioFixo

escreval("o salario do(a) ",nome," total desse mes foi de: ",tot)

Fimalgoritmo
====================================================================================
Atividade 5 de portugol : escreva um algoritmo que leia A e B, e efetue a troca dos valores
de forma que A receba B e B receba A, e apresente os numeros trocados.
Algoritmo "trocaDeVariaveis"

Var
   a,b,c : caracter

Inicio
      escreva("digite qual o primeiro variavel: ")
      leia(a)
      escreva("digite qual o segunda variavel: ")
      leia(b)
      escreval("valor de A = ",a," valor de B = ",b)
      c:= b
      b:= a
      a:= c
      
      escreval("----troca----")
      escreval("valor de A = ",a," valor de B = ",b)


Fimalgoritmo
