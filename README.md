nome = ['Lucas Melo','Jonathas Coelho','Jhonata Freixihno','Gabriela Freixinho']
altura = [1.70, 1.75, 1.79, 1.66]
peso = [53, 70, 83, 76]
imc = [0, 0, 0, 0]

imc[0] = peso[0]/(altura[0] * altura[0])
imc[1] = peso[1]/(altura[1] * altura[1])
imc[2] = peso[2]/(altura[2] * altura[2])
imc[3] = peso[3]/(altura[3] * altura[3])

print('\nNome:', nome[0], '\nAltura;', altura[0], '\nPeso:', peso[0], '\nÍndice de massa corpórea:', imc[0])
print(' ')
print(nome[1], '\nAltura;', altura[1], '\nPeso:', peso[1], '\nÍndice de massa corpórea:', imc[1])
print(' ')
print(nome[2], '\nAltura;', altura[2], '\nPeso:', peso[2], '\nÍndice de massa corpórea:', imc[2])
print(' ')
print(nome[3], '\nAltura;', altura[3], '\nPeso:', peso[3], '\nÍndice de massa corpórea:', imc[3])
