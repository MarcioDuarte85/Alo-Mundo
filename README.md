# Alo-Mundo
Meu primeiro projeto
Novas alteraçoes
escreva "Digite seu peso"
var peso := leia_numero
escreva "Digite sua altura"
var altura := leia_numero

var imc := peso/(altura * altura)

escreva "{imc}"
se imc < 17 então
	escreva "Muito abaixo do peso
senão
se imc >= 17 |e| imc <= 18.49 então
    escreva "Abaixo do peso"
senão
se imc >= 18.50 |e| imc <= 24.99 então
    escreva "Peso normal"
senão
se imc >= 25 |e| imc <= 29.99 então
    escreva "Acima do peso"
senão
se imc >= 30 |e| imc <= 34.99 então
    escreva "Obesidade I"
senão
se imc >= 35 |e| imc <= 39.99 então
     escreva "Obesidade II(severa)"
senão
se imc >= 40 então
   	escreva "Obesidade III(mórbida)"
	fim
fim
