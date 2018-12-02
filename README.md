# PYTHON
Python é uma linguagem que eu gosto muito, é extremamente facil sua aprendizado e sua sintaxe é muito simples. Obrigado Guido Van Rossum.

``` python
  ## Para Iniciar Bem :)
  print("Hello World")

```

## Variaveis
As variaveis em Python são criadas no momento que você atribui valores a ela. Também não é necessario especificar um tipo, pois são mutaveis.

``` python
  x = "Christiano"  # String
  x = 10  # Int
  x = 2.8 # Float 
```

## Entrada de Dados
Podemos receber um valor fazendo uso do comando input, esse valor será transformado em string.

``` python
a = input("Digite algo:")
print(a)
```

## Operadores
```python
#soma
>>> 5+5
10

#subtração
>>> 10-2
8

#multiplicação
>>> 2*2
4

#divisão
>>> 81/9
9.0

#exponenciação
>>> 2**5
32

#extração da parte inteira da divisão
>>> 10//9
1
```


## Condições
### IF Simples
``` python
if 1 > 2:
  print("Verdadeiro")
else:
  print("Falso")
  
``` 
### IF Encadeado
``` python
idade = 18
if idade < 12:
  print('criança')
elif idade < 18:
  print('adolescente')
elif idade < 60:
  print('adulto')
else:
  print('idoso')
``` 

## Repetições

``` python
i = 1
while i < 6:
  print(i)
  i += 1
  
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  
```
## Listas

``` python
l = []  # Lista Vazia
l = ["a",1,5.5]  # Lista com elementos

thislist = ["apple", "banana", "cherry"]
print(thislist)

thislist = ["apple", "banana", "cherry"]
print(thislist[1]) #Imprimer determinado elemento

#adicionar elemento na lista
thislist.append("orange")

#remover elemento da lista, basta usar o comando del e passar qual a posição do elemento
del thislist[1]

```

## Funções
``` python
#cria a função
def my_function():
  print("Hello from a function")

#chama a função
my_function()
  
```
## Bibliotecas
## Math
Math é uma biblioteca que contem função para fazer calculos matematicos
https://docs.python.org/2/library/math.html
``` python
import math

#Potencia
>>>print(math.pow(9,5))
59049.0

#Raiz Quadrada
>>>print(math.sqrt(25))
5

#Maior Divisor Comum
>>>print(math.gcd(10,2))
2

#Teto
>>>print(math.ceil(10.5))
11

#Piso
>>>print(math.floor(10.5))
10

#Fatorial
>>>print(math.factorial(5))
120
```
