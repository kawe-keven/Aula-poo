# Projeto de Programação Orientada a Objetos (POO) em Python

Este pequeno projeto demonstra o conceito de **Classes e Objetos** em Python, criando uma classe simples para representar um aluno.

## Classe: `Aluno`

A classe `Aluno` possui os seguintes atributos e métodos:

### Atributos:
* `nome`: O nome do aluno (string).
* `idade`: A idade do aluno (inteiro).

### Métodos:
* `__init__(self, nome, idade)`: O construtor, usado para inicializar o `nome` e a `idade` ao criar o objeto.
* `estudar(self)`: Simula a ação de estudar e imprime uma mensagem.
* `apresentar(self)`: Apresenta o aluno, imprimindo seu nome e idade.

## Exemplo de Uso

O exemplo abaixo mostra como a classe é utilizada, criando um objeto chamado `aluno1` e chamando seus métodos:

```python
class Aluno:
    # ... (definição completa da classe) ...
    def __init__(self, nome, idade):
        self.nome = nome
        self.idade = idade
    
    def estudar(self):
        print(f"{self.nome} está focado em seus estudos.")

    def apresentar(self):
        print(f"Olá! Meu nome é {self.nome} e eu tenho {self.idade} anos.")

# 1. Criar um objeto da classe Aluno
aluno1 = Aluno(nome="Maria", idade=20)

# 2. Chamar os métodos
aluno1.apresentar()
# Saída: Olá! Meu nome é Maria e eu tenho 20 anos.

aluno1.estudar()
# Saída: Maria está focado em seus estudos.
