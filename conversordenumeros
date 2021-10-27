from sys import exit

print ("=-"*17)
print ("=-"*7 , "MENU", "=-"*7)
print ("conversor de bases numéricas ".upper())
print ("[A] Converter numero para base binária")
print ("[B] Converter numero para base hexadecimal")
print ("[C] Converter número para base octadecimal")
alternativa =  str (input("Para selecionar, digite a letra que corresponde á sua opção:"))

if alternativa not in ("A", "B", "C", "a",  "b", "c"):
        print ("Alternativa inválida, digite A , B ou C")
        exit()

novamente = str(input('Digite novamente para confirmar'))

if alternativa != novamente:
        print ("Alternativa inválida, digite igualmente as duas opções")
        print ("=-"*7, "fim de programa", "=-"*7)
        exit()
######### Se uma alternativa for diferente da outra o programa encerra#########
num = int (input ("digite o numero que deseja converter"))

if alternativa in ('A' , 'a'):
    if novamente in ('A' , 'a'):
        print ("O seu numero em binário é {} \nFIM DE PROGRAMA".format(bin(num)))
        print("=-" * 7, "fim de programa", "=-" * 7)
        exit()
elif alternativa in ('B' , 'b'):
    if novamente in ('B' , 'b'):
        print ("O seu numero em hexadecimal é {} \n FIM DE PROGRAMA".format (hex(num)))
        print("=-" * 7, "fim de programa", "=-" * 7)
        exit()
elif alternativa == 'C':
    if novamente == 'C':
        print ("O seu numero em octadecimal é {} \n FIM DE PROGRAMA".format (oct(num)))
        print("=-" * 7, "fim de programa", "=-" * 7)
        exit()
else:
        print ("Esta alternativa está incorreta, tente novamente")
        print("=-" * 7, "fim de programa", "=-" * 7)
        exit()
