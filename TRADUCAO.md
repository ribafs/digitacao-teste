# Como gerar o array

## Com palavras em português delimitadas por aspas

Procurei um texto contendo as palavras. Eliminei as vírgulas, pontos e letras em maiúsculas. Tentei eliminar as palavras repetidas.
Copiei o texto e colei em um arquivo no VSCode. Então pesquisei todas as ocorrências de espaço em branco e as substitui por ", ".

Eu tinha isso:

procurei um texto contendo as palavras

E o VSCode me devolve isso:

procurei" "um" "texto" "contendo" "as" "palavras

Faltou apenas colocar as aspas no início da primeira palavra e ao final da última.


