# desafio_02

# Número de testes
N = int(input())

for _ in range(N):
    A, B = input().split()

    # Verifica se B é o final de A
    if A[-len(B):] == B:
        print("encaixa")
    else:
        print("nao encaixa")
