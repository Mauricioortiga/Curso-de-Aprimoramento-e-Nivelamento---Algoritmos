<img width="907" height="491" alt="image" src="https://github.com/user-attachments/assets/708509b0-e11b-498d-af34-4ae7aa5473c1" />

algoritmo "Cadastro de Livros"

var
  titulo1, titulo2, autor1, autor2 : caractere
  anopublicacao1, anopublicacao2 : inteiro
  disponivel : logico

inicio

escreva ("Digite o título do primeiro livro: ")
leia (titulo1)
escreva ("Digite o título do segundo livro: ")
leia (titulo2)
escreva ("Digite o ano de publicação do primeiro livro: ")
leia (anopublicacao1)
escreva ("Digite o ano de publicação do segundo livro: ")
leia (anopublicacao2)
escreva ("Digite o nome do autor do primeiro livro: ")
leia (autor1)
escreva ("Digite o nome do autor do segundo livro: ")
leia (autor2)
disponivel <- verdadeiro
escreva ("Ficha do primeiro livro: ", titulo1, "-", autor1, "-", anopublicacao1, )
escreva ("Fica do segundo livro: ", titulo2, "-", autor2, "-", anopublicacao2)
fimalgoritmo
