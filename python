print('CONSULTAR MATRICULA')

texto = 1

while texto == 1:
		
		#obtendo o nome e a idade do usuário
    nome = input('Nome da criança:')
    idade = int(input('Idade:'))
		
		#para cada intervalo o usuario será encaixado em uma dessas categorias
    if (idade >= 1 and idade <= 5):
        print('\n A Aluna(o) {}, tem {} anos e está na Educação Infantil!'.format(nome, idade))
    elif (idade >= 6 and idade <= 10):
        print('\n A Aluna(o) {}, tem {} anos e está no Ensino Fundamental I!'.format(nome, idade))
    elif (idade >= 11 and idade <= 14):
        print('\n A Aluna(o) {}, tem {} anos e está no Ensino Fundamental II!'.format(nome,idade))
    elif (idade >= 15):
        print('\n A Aluna(o) {}, tem {} anos e está no Ensino Médio!'.format(nome, idade))
		
		#se o usuário digitar 0 ele sai do programa, se digitar 1 ela continua e é solicitado o nome e idade do usuário novamente
    texto = int(input('Deseja continuar? 0 - Não   1 - Sim\n'))
		
		#se ele digitar 0 sai do programa
    if (texto == 0):
        print('Encerrando o programa...')
        break
