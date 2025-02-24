#Textos
print("Hello word")
print("24/02/2025 Aula 1")

nome = "Leandro" 
idade = 20       
print("O aluno",nome,"tem",idade,"anos")
print(f"O aluno {nome} tem {idade} anos")

nome = "Nogueira" 
idade = 19       
print("O aluno",nome,"tem",idade,"anos")
print(f"O aluno {nome} tem {idade} anos")

# operações:

n1 = 10
n2 = 15

print(n1*n2)
print(n1+n2)
print(n1/n2)
print(n1-n2)
print(n1**n2)
print(n1//n2)
print(n1%n2)

#Bolleans
n1 = 20
n2 = 30
print("Maior que",(n1>n2))
print("Menor que",(n1<n2))
print("Igual a",(n1==n2))
print("Diferente de",(n1!=n2))
import sys
print(sys.version)

#entrada e saída:
nome = input("Digite o seu nome ") 
salario = float (input("digite o salário "))
idade = int (input("digite sua idade "))
print (f"O funcionário {nome}, tem {idade} anos e recebe R${salario}")
