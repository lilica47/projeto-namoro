import random
import time

print("💖 Bem-vindo ao Simulador de Namoro 💖")
nome = input("Qual é o seu nome? ")
crush = input("Qual é o nome da pessoa que você gosta? ")

print("\nCalculando compatibilidade amorosa...")
time.sleep(2)

# Compatibilidade aleatória entre 50% e 100%
compatibilidade = random.randint(50, 100)

print(f"\n{nome} ❤️ {crush} = {compatibilidade}% de compatibilidade!")

# Resposta divertida dependendo do resultado
if compatibilidade >= 90:
    print("💍 Alma gêmea detectada! Prepare o casamento!")
elif compatibilidade >= 70:
    print("😍 Vocês têm tudo para dar certo!")
elif compatibilidade >= 50:
    print("🙂 Pode dar certo, mas precisa de mais conexão...")
else:
    print("🙃 Melhor continuar como amigos...")

print("\nFim do programa. Boa sorte no amor! 💘")
