# Calculadora-de-absenteismo
fiz essa calculadora para ajudar em admiração e gestação hospitalar ela está em PYTHON.
#{calculadora de absenteismo} ...vapo...
colab = float(input('digite o total de colaboradores'))
faltas = float(input('digite o total de faltas e atrasos'))
colab2 = float(input('digite o total de colaboradores'))
diastrab = float(input('digite o total de dias trabalhados'))
absenteismo = (colab * faltas) / (colab2 * diastrab)*500

print(absenteismo,"esse é o resultado")
