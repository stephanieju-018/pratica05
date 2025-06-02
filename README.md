# pratica05
Definindo Funções
def saudacao(stephanie):
    print("Olá, mundo!")
def soma(a, b):
    return a + b
resultado = soma(3, 4)
print(resultado)
def saudacao(nome="usuário"):
    print(f"Olá, {nome}!")
x = 5  # global

def exemplo():
    x = 10  # local
    print(x)

exemplo()
print(x)
def externa():
    def interna():
        print("Função interna")
    interna()
