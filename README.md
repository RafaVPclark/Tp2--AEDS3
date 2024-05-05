# Tp2--AEDS3
## Métodos Implementados/Alterados
### NA CLASSE ARQUIVO LIVROS
* Método tratarTitulo()
Esse método foi criado para receber um titulo com diversas palavras, separar elas utilizando um split, transformas todas em palavras minúsculas, remover os acentos e as stop words. Após realizar a formatação ele retorna um vetor de Strings.
* Método isStopWord()
Método criado para comparar uma das palavras do titulo e retornar um valor booleano caso seja uma das stopWords selecionadas
* Método Create()
No momento de inserção é adicionada cada uma das palavras tratadas no título com o  respectivo id que lhe foi atribuído para a lista invertida.
* Método Delete()
De forma análoga com o método anterior, após recuperar o objeto pelo id, o título foi tratado e removido da lista, um por um.
*Método Update()
Esse método foi uma junção do Create() com o Delete(), no qual nós apagamos da lista invertida os valores do titulo do objeto antigo e inserimos novamente nela os valores do titulo novo.
*Método  buscarNomeLivro()
Esse método foi criado para realizar a pesquisa utilizando as palavras chaves informados no teclado, esse método recebe uma String, trata ela e realiza uma busca de cada palavra para receber o vetor de inteiros com os ids que essas palavras se encontram, com peso de ordem de chegada. Após receber esse vetor de inteiros da primeira palavra, ele compara esse vetor com o vetor obtido da segunda palavra e realiza uma concatenação. Após realizar esse procedimento com todas as palavras ele retorna oS ids obtido a partir dessas concatenações em sequência.
* Método vetorIIntersecao
Recebe dois vetores de inteiros e retorna um terceiro vetor com a interseção dos dois.
### NA CLASSE MENU LIVROS
* Método buscarLivroNome()
é o método que aparece na tela para o usuário e utiliza o outro método(buscarNomeLivro- da classe arquivo livros) para realizar a busca utilizando o titulo inserido na tela.

### RESTANTE
Além de tudo isso na classe principal, foi adicionado um delete() para apagar os dados do dicionário da lista invertida.

### Opinião do grupo
Todos os requisitos foram alcançados, e os métodos de create, update e delete foram tranquilos após a compreensão da classe ListaInvertida. O trabalho maior foi criar o método que formatasse corretamente os titulos, e, principalmente o método de busca. Não sabiamos como funcionava esse método, porém após compreender que ele retornava um vetor com os ids pensamos em ficar realizando uma junção de valores comuns em sequência e ficou mais tranquilo. Porém no fim todos os resultados foram alcançados e os métodos estão funcionando corretamente.

# CHECKLIST
* A inclusão de um livro acrescenta os termos do seu título à lista invertida? SIM 
* A alteração de um livro modifica a lista invertida removendo ou acrescentando termos do título? SIM
* A remoção de um livro gera a remoção dos termos do seu título na lista invertida? SIM
* Há uma busca por palavras que retorna os livros que possuam essas palavras? SIM
* Essa busca pode ser feita com mais de uma palavra? SIM
* As stop words foram removidas de todo o processo? SIM
* Que modificação, se alguma, você fez para além dos requisitos mínimos desta tarefa? NENHUMA
* O trabalho está funcionando corretamente? SIM
* O trabalho está completo? SIM
* O trabalho é original e não a cópia de um trabalho de um colega? SIM
