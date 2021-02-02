# Python-
Programa calcular valor desconto IR

# Entrada de dados

nome       = input("Nome:               ")
dt_nasc    = input("Data de Nascimento: ")
idade      = input("Idade:              ")
cpf        = input("CPF:                ") 
rg         = input("RG:                 ")
endereco   = input("Endereço:           ")
email      = input("Email:              ")
telefone   = input("Telefone:           ")
sexo       = input("Sexo:               ")
empr_ativo = input("Empregado Ativo:    ")

# Cálculo IR

salario     = float(input("Salário:     "))
imp_renda   = salario * 0.15
salario_liq = salario - imp_renda

#Saída de dados

print("-----------------------------------")

print("Nome:               " +nome)
print("Data de Nascimento: " +dt_nasc)
print("Idade:              " +idade)
print("CPF:                " +cpf)
print("RG:                 " +rg)
print("Endereço:           " +endereco)
print("Email:              " +email)
print("Telefone:           " +telefone)
print("Sexo:               " +sexo)
print("Empregado Ativo     " +empr_ativo)
print("Salário Liquido:    " +salario_liq)
