#solicita ao usuário um número
numero_informado = int(input("Informe um número: "))

def verifica_fibonacci(numero):
    a, b = 0, 1
    while b < numero:
        a, b = b, a + b
    if b == numero:
        return f"{numero} pertence à sequência de Fibonacci."
    else:
        return f"{numero} não pertence à sequência de Fibonacci."
    
#chama a função e exibi o resultado
resultado = verifica_fibonacci(numero_informado)
print(resultado)
