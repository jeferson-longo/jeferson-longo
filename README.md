class MeuNome:
    def __init__(self, nome, interesse, curso, colaboracao, linkedin):
        self.nome = nome
        self.interesse = interesse
        self.curso = curso
        self.colaboracao = colaboracao
        self.linkedin = linkedin
        
    
    def MostraLinha(self):
        print('*' * 30)

    def Nome(self):
        print(f'Olá, meu nome é {self.nome}')

    def Interesse(self):
        print(f'Estou interessado em Programação')

    def Curso(self):
        print(f'Estou me desenvolvendo em Python')

    def Colaboracao(self):
        print(f'Pretendo colaborar em projetos feitos em Python')

    def Linkedin(self):
        print('Podem me localizar através do www.linkedin.com/in/jeferson-longo')


meu_nome = MeuNome('Jeferson Longo', 'Programação', 'Python', 'Projetos Python', 'jeferson-longo')


meu_nome.Nome()
meu_nome.Interesse()
meu_nome.Curso()
meu_nome.Colaboracao()
meu_nome.Linkedin()
