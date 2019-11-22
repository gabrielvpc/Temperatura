import os

print ("\nSelecione uma das opções abaixo: \n\n 1=Celsius para Fahrenheit \n 2=Celsius para Kelvin \n 3=Kelvin para Celsius \n 4=Kelvin para Fahrenheit \n 5=Fahrenheit para Celsius \n 6=Fahrenheit para Kelvin \n")
menu=int(input("> "))
if menu == 1:
	temp=float(input("\nInsira a temperatura em Celsius \n\n> "))
	tempF=float((temp*9+160)/5)
	print(tempF , end=" Graus Fahrenheit\n") 
elif menu == 2:
	temp=float(input("\nInsira a temperatura em Celsius \n\n> "))
	print(temp + 273.15 , end=" Graus Kelvin\n")
elif menu == 3:
	temp=float(input("\nInsira a temperatura em Kelvin \n\n> "))
	print(temp - 273.15 , end=" Graus Celsius\n")
elif menu == 4:
	temp=float(input("\nInsira a temperatura em Kelvin \n\n> "))
	tempK=float((temp-273.15)*9+160)/5
	print(tempK , end=" Graus Fahrenheit\n")
elif menu == 5:
	temp=int(input("\nInsira a temperatura em Fahrenheit \n\n> "))
	tempC=float((temp-32)*5)/9
	print(tempC , end=" Graus Celsius\n")
elif menu == 6:
	temp=float(input("\nInsira a temperatura em Fahrenheit \n\n> "))
	tempF=(float((temp-32)*5+2458.35)/9)
	print(tempF , end=" Graus Kelvin\n")
else:
	print("\n Insira apenas números de 1 a 6 !! \n")
	exit
