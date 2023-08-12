# Calculo-de-ano-em-Python
NOME = input ("Digite seu nome: ")
IDADE = int(input("Digite a sua idade: "))
print (NOME, "O ano de seu nascimento é: ", 2023-IDADE)
SALDO = float(input( "Seu saldo é de: "))
PERCENT = ((SALDO*30)/100+SALDO)
print ("Seu saldo é de: ", SALDO, "Com percentual: ", PERCENT)
print (f"Você {NOME} que nasceu em {2023-IDADE} terá um saldo de {PERCENT}%, que terá um de R$ {SALDO + PERCENT}")
