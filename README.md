# Digite só letrasn e não numeros

EXERCICIOS DE INICIANTE DE PYTHON.
nome = str(input('Digite seu primeiro nome: '))
tamanho = len(nome)
if nome.isalpha():
    if tamanho <= 4:
        print(f'{nome} seu nome é muito CURTO.')
    elif tamanho <= 6:
        print(f'{nome} seu nome é NORMAL.')
    else:
        print(f'{nome} seu nome é MUITO GRANDE.')
else:
    print('Você digitou NÚMEROS... Digite seu nome!!!')
