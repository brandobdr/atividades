class NOME:
  def nomedousuario(self):
    self.nome = input("Como se chama?: ")
    print(f"Seja bem-vindo ao nosso site, {self.nome}!")

usuario = NOME()
usuario.nomedousuario()

class PESO:
  def pesodousuario(self):
    self.peso = float (input("Qual é o seu peso?: "))
    print(f"Certo, seu peso é: {self.peso}")

peso = PESO()
peso.pesodousuario()

class ALTURA:
  def alturadousuario(self):
    self.altura = float (input("Qual é a sua altura?: "))
    print(f"Certo, sua altura é: {self.altura}")

altura = ALTURA()
altura.alturadousuario()

class IMC:
  def calcular(self, peso, altura):
    print("Calculando IMC...")
    imc = peso/(altura ** 2)
    print(f"Seu IMC é: {imc:.2f}")

    if imc <18.5:
      print("Você está abaixo do peso.")
    elif imc <= 24.9:
      print("Seu peso está normal.")
    elif imc <= 29.9:
      print("Você está com sobrepreso.")
    elif imc >30:
      print("Você está com obesidade.")

imc = IMC()
imc.calcular(peso.peso, altura.altura)