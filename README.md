# project
#o objetivo do construtor é reduzir a passagem de parametros 
#(passar or argumentos de uma forma mais simples)
class Professor:

  def __init__(self,nome, sobrenome):
    self.nome = nome
    self.sobrenome = sobrenome

  '''criando mais uma função dentro da classe que vai puxar os 
  dados passados como   parametros nos objetos usuario1 e usuario2. 
  Precisamos apenas utilizar o self, pois 
  os agumentos ja foram passados na função acima.''' 
  
  def nome_completo(self):
    return self.nome + ' ' + self.sobrenome    
  
#criando dois objetos e realizando a passagem de parametros
usuario1 = Professor('Victor', 'Sotero')
usuario2 = Professor('Ana', 'Maria')

#chamando a função nome_completo()
print(usuario1.nome_completo())
    
