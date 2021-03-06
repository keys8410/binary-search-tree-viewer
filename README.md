# VISUALIZADOR DE ÁRVORE BINÁRIA DE BUSCA
- Montagem >> árvore binária de busca:
	- Inserção.
	- Remoção.
	- exibição: 
	- árvore completa - raiz, sub-arv. esquerda e sub-arv. direita;
	    - em ordem;
	    - pré-ordem;
	    - pós-ordem;					
	- Buscar elemento na árvore - mostragem de tempo de busca

## [Definição](https://pt.wikipedia.org/wiki/%C3%81rvore_bin%C3%A1ria_de_busca)
- Em Ciência da computação, uma **árvore binária de busca** (ou **árvore binária de pesquisa**) é uma estrutura de dados de árvore binária baseada em nós, onde todos os nós da subárvore esquerda possuem um valor numérico inferior ao nó raiz e todos os nós da subárvore direita possuem um valor superior ao nó raiz (esta é a forma padrão, podendo as subárvores serem invertidas, 	dependendo da aplicação).

> O objetivo desta árvore é estruturar os dados de forma a permitir busca binária.

### Execução - *.exe

'BSTV' requer [winRAR](https://www.win-rar.com/start.html?&L=0) (*ou similar*) para descompactá-lo.

![Screenshot_540](https://user-images.githubusercontent.com/56321281/77133936-b9284a80-6a43-11ea-91b4-e91c511b6ede.png)   
[Download](https://github.com/keys8410/binary-search-tree-viewer/blob/master/Binary%20Search%20Tree%20Viewer.zip)
> Há uma pasta dentro nomeada como 'files'. **Não a exclua!**

<br>

- Arquivo gerado dentro do diretório 'files': *.txt

> Exemplo de backup < b >

![Screenshot_544](https://user-images.githubusercontent.com/56321281/77137254-e4169c80-6a4b-11ea-923a-f6d23ee12bcb.png)

### Execução - *.dev

> Cabeçalhos nativos:

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <conio.h>
#include <time.h>
```
<br>

> Cabeçalhos não nativos

```c
#include "headers/conio2.h" 
#include "headers/bst.h" 
#include "headers/cmd.h"
```
Estrutura dentro do arquivo *.dev

[Download](https://github.com/keys8410/binary-search-tree-viewer/blob/master/bin_.zip) *.dev

![Screenshot_543](https://user-images.githubusercontent.com/56321281/77134269-f6410c80-6a44-11ea-9312-98af48fc14fe.png)

<br>

### Comandos - *duplo ambiente*

#### Prompt de Comando

> Ambiente de aprendizagem: 

| Commands: | Performs |
| ------ | ------ |
| /help | 'this command shows included command options.' |
| /+ | 'this command adds an element.' |
| /- | 'this command removes an element.' |
| /esc | 'this command ends the process.' |
| /main | 'this command starts program execution - main/bin_tree.' |
<br>

#### main/bin_tree

> Ambiente de execução:

| Keys: | Performs |
| ------ | ------ |
| + | 'this key adds an element.' |
| - | 'this key removes an element.' |
| esc | 'this key ends the process.' |
| m | 'this key adds random numbers in the tree' |
| r | 'this key free the tree - turns it empty' |
| s | 'this key searchs a number in the tree' |
| b | 'this key do an backup in external archive' |

### Referência bibliográfica
* [[01]](http://ninjacode.com.br/arvore-binaria-com-a-linguagem-c/) - Árvore Binária com a Linguagem C
* [[02]](https://pt.wikibooks.org/wiki/Programar_em_C/%C3%81rvores_bin%C3%A1rias_de_Busca) - Programar em C - Árvores binárias de Busca
* [[03]](https://www.cin.ufpe.br/~dmrac/aula%20de%20arvore%20binaria%20de%20busca.pdf) - Árvores Binárias de Busca

<br>

### Dados

    Autor: Yan Almeida Garcia - 2019 199 05
    Departamento de T.I., UniProjeção (Taguatinga, Campus I)
    Sistemas de Informação (3º semestre) - 1º/2020
    Disciplina: Estrutura de Dados - João Evangelista
    
<br><br>

License
----
APACHE 2.0

> *Software Livre!* 
Use-o como base para estudos e afins.
