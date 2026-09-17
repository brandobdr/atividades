import random

class SENHA:
    def gerarsenha(self):
        caracteres = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789"

        quantidade = int(input("Digite a quantidade de caracteres: "))

        senha = ""

        for i in range(quantidade):
            senha += random.choice(caracteres)

        print(f"Senha gerada: {senha}")


senha = SENHA()
senha.gerarsenha()