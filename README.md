# Exercicios-em-Python
exercicios em python basico

#Exercicio em Python

#1-escrevar Olá mundo.

print ('Olá Mundo')

#2-Digite seu nome e faça aparecer>E um prazer te conhecer_____.

nome=input("digite seu nome")

print('é um prazer te conhecer,{}'.fomat(nome))

#3-faça que apareça o dia mes e ano que voce nasceu.


dia=input('dia')

mes= input ('mes')

ano= input('Ano')


print('voce nasceu em{} de {} de {}'.fomat.(dia, mes , ano))

#4-faça a soma de dois numeros

n1= int(input('digite um numero: '))
n2=int(input('digite mais um numero: '))
s=n1+n2


print('a soma entre {} e {} vale {}.'format(n1, n2, s))

#5- escolha um numero e faça o seu antecessor e seu sucessor aparecer.

n= int(input('digite um numero: '))

pinr('o valor é {}, seu antecessor é{}, e seu sucessor é {}'.format(n, n-1, n+1))

#6- cire um  algoritimo que leia um numero, e mostre seu dobro,triplo e a raiz quadrada

n=int(input('digite um numero'))
d= n*2
t= n*3
r= n**(1/2)

print('O dobro de {} vale {}'.fomat(n,d))

print('o triplo de {} vale {}, e a raiz quadra de {} é {}'.format(n,t,n,r))


#7- desenvolva um programa que leia as duas notas de um aluno e calcule a media e mostre ela.

n1=float (input('primeira nota: '))
n2= float (input('segunda nota: '))
m=(n1+n2)/2

print('a media entre {} e {},é igual a {}'.fomat(n1, n2, m))

#8- escreva um programa que leia um valor em metros e o exiba convertido em cm e mm.

medida= float(input('Uma distancia em metros: '))
cm=
mm=


print('a medida de {}m correspode a {}cm e {}mm'.fomat(medida,cm, mm))

#9- Faça um programa que leia um numero inteiro qualquer e mostre na tela a sua tabuada.

num=int(input('digite um número para ver sua tabuada'))
print('-'*12)
print('{} x {:2} = {}'.format(num, 1, num*1))
print('{}x {:2} = {}'.format(num, 2, num*2))
print('{}x {:2} = {}'.format(num, 3, num*3))
print('{}x {:2} = {}'.format(num, 4, num*4))
print('{}x {:2} = {}'.format(num, 5, num*5))
print('{}x {:2} = {}'.format(num, 6, num*6))
print('{}x {:2} = {}'.format(num, 7, num*7))
print('{}x {:2} = {}'.format(num, 8, num*8))
print('{}x {:2} = {}'.format(num, 9, num*9))
print('{}x {:2} = {}'.format(num, 10, num*10)) 
print('-'*12)
