# ping

import os  

pingando = input("digite o ip: ")

os.system(f"ping -n 6 {pingando}")

'''acima estou chamando da biblioteca os o system e dando
 o comando entre parenteses no caso "ping" e o -n é o numeo de pacotes ping que vou enviar
 por fim estou trazendo da variavel pingando o ip do alvo'''
 
