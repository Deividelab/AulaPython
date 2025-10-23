# AulaPython
Aulas referente ao curso de Python do IFBAIANO.

#FUNÇÕES  *possuem o ()
#print() - Saída
#input() - Entrda

#CASTING:
#O input sempre retorna str alguma das vezes é necessário converter para o tipo correto

#TIPOS DE DADOS PRIMITIVOS

a = 10        #int - Números inteiros
b = 3.14      #float - #Números decimais
c = True      #bool - Valores lógicos
d = "Python"  #str - Texto ou sequência de caracteres ("Olá, "Python")

print(type(a))
print(type(b))
print(type(c))
print(type(d))

#EXERCÍCIO 1 - DADOS PRIMITIVOS
Nome = "Davi"
Idade = 18
Altura = 1.73
Gosto_de_Python = True

print("Nome:", Nome, type(Nome))
print("Idade:", Idade, type(Idade))
print("Altura:", Altura, type(Altura))
print("Gosta de pyton:", Gosto_de_Pyton, type(Gosto_de_Python))

# O python é um linguagem de tipagem dinâmica - Diferente de outras linguagens como o Java, não é necessário especificar qual o tipo da variável

#EXERCÍCIO 1 - DADOS PRIMITIVOS
Nome = "Davi"
Idade = 18
Altura = 1.73
Gosto_de_Python = True

print("Nome:", Nome, type(Nome))
print("Idade:", Idade, type(Idade))
print("Altura:", Altura, type(Altura))
print("Gosta de pyton:", Gosto_de_Pyton, type(Gosto_de_Python))

# O python é um linguagem de tipagem dinâmica - Diferente de outras linguagens como o Java, não é necessário especificar qual o tipo da variável

#SEGUNDO CADASTRO
Int = 18
Float = 19
A = 18
B = 18,5

print(A)
print(B)

#SALÁRIO
Bufunfa = float(input("Informe o deposito: "))
Aumento = float(input("Informe o percentual de aumento: "))
# Quando usamos "imput" o sistema entende que o está dentro do () é uma STRING
# Como se trata de números temos que ultilizar o "float" - Decimal

print(Bufunfa + (Bufunfa * Aumento/100))

#SALÁRIO 2
Bufunfa = float(input("Informe o deposito: "))
Aumento = float(input("Informe o percentual de aumento: "))

Novo_Valor = Bufunfa + (Bufunfa * Aumento / 100)

print(f"Valor com aumento: R$ {Novo_Valor:.2f}")
#print("%8.3f"Bufunfa + (Bufunfa * Aumento)
