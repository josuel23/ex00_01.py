# exercicio_orientado_a_objeto

class Carro:

    def __init__(self):

        self.modelo = None
        self.ano = 0
        self.cor = None

    def exibir_caracteristicas(self):

        print('modelo:', self.modelo)
        print('ano:', self.ano)
        print('cor:', self.cor)

meu_carro = Carro()
meu_carro.modelo = 'HB 20'
meu_carro.ano = 2020
meu_carro.cor = 'preto'
meu_carro.exibir_caracteristicas()
