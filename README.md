# laranjo
git add <>


-- Progresso --

13/08 - Decidimos o tema do projeto

20/08 - Criamos o MER e iniciamos a base do projeto (criação do site)

27/08 - Criação das tabelas baseadas no MER

=========================================================================================


https://www.caelum.com.br/apostila-html-css-javascript/apendice-php-banco-de-dados-e-sql/#buscas-no-my
sql-com-php

site sobre autistas
https://pt.slideshare.net/SimoneHelenDrumond/75-jogos-e-brincadeiras-na-aprendizagem-do-autista-por-simone-helen-drumond


//declarar estado incial do bicho
//select de todos as perguntas com a emocao x, e aí um random dentro

PERGUNTA---------------------
codPergunta(pk)      codEmocao(fk)     valorPerg(ntext)        
1                           1            nome?
2                           3            idade?      

EMOCAO----------------------
codEmocao(pk)    nome(ntext) 
1                  feliz
2                  triste

RESPOSTA--------------------
codPergunta(fk)  codResp(pk)     valorResp(ntext)      codEmocao(fk)
1                  1               fodase                 1
1                  2               nao sei                2
1                  3               julio                  3
2                  1
2                  2
2                  3
