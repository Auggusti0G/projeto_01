# projeto_01

soma = 0
quantidade = 0

print("Digite as notas dos alunos (digite 0 para encerrar):")

# Loop com while
while True:
    nota = float(input("Digite uma nota: "))

    if nota == 0:
        break  # Encerra o loop se o usuário digitar 0

    soma += nota
    quantidade += 1

# Verificação se alguma nota foi digitada
if quantidade > 0:
    media = soma / quantidade
    print(f"\nMédia aritmética da turma: {media:.2f}")
    print(f"Quantidade de notas digitadas: {quantidade}")
else:
    print("\nNenhuma nota foi digitada.")
