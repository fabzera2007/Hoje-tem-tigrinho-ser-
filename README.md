# devo apostar?
Saiba se você está com sorte hoje, adivinhando um número entre 1 a 10, com 2 chances.

print("DEVO APOSTAR? \n")

import random

numero_aleatorio = random.randint(1, 10)

guess = 0
tries = 0

while guess != numero_aleatorio and tries < 2:
  guess = int(input('Fala um número ai de 1 a 10:  '))
  tries = tries + 1

if guess != numero_aleatorio:
  print('Ta com azar hj nem tenta.')
else:
  print('Vai na fé!')


