# 1) Por que o número de filhos, ou grau, de um nó de uma árvore B qualquer não pode ser igual a 1? 
De acordo com os autores Bayer e McCreight, dentre outros, definem a ordem como sendo o número mínimo de chaves que uma página pode conter, mas essa definição pode causar ambiguidades quando se quer armazenar um número máximo ímpar de chaves. Assim, para evitar a ambiguidade, Knuth propôs que a ordem de uma árvore B fosse o número máximo de páginas filhas que toda página poderia conter. Dessa forma, o número máximo de chaves por página ficou estabelecido como a ordem menos um, que também foi usado para as outras partes da árvore B.
# 2) Para que valores de ordem da árvore da figura abaixo é uma árvore B válida?  

# 3) Mostre todas as árvores B válidas de ordem d = 1 que possuem as seguintes chaves {1,2,3,4,5}. 

# 4) Explique como encontrar a maior chave armazenada em uma árvore B.
Para encontrar a maior chave, o primeiro passo é verficar se a maior chave da página raiz possui uma ponteiro para uma outra página, caso tenha, repetir o mesmo passo para a página atual, e assim sucessivamente até que seja encontrado uma chave que não possui um ponteiro. Dessa forma, essa chave é a maior chave da árvore B.

# 5) Desenhe, passo a passo, uma árvore B de ordem d = 2 inserindo as seguintes chaves na ordem em que estão sendo informadas: 99, 50, 60, 37, 45, 15, 28, 40, 58, 89, 70, 65, 59,48, 49, 53. 

# 6) Sobre a árvore resultante do exercício anterior, ilustre, passo a passo, as seguintes operações:
* a) Inserir, também na ordem em que são informadas, as chaves 47, 46, 39, 52, 51, 55 (notar que as inserções são cumulativas).
* b) Sobre o resultado do passo (a), excluir as chaves 37, 47, 46 e 65, na ordem informada. Notar que as exclusões são cumulativas.
