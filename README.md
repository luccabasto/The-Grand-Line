            Desenvolvendo um página com referência a NETFLIX - 7DaysOfCode


* As atualizações esta organizado a partir das atualizações mais recentes.

          ========= TAREFA #05 - 06/11/23  ======>

  Consegui desenvolver o trilho, implementei dois grupos seguindo determinado padrão grid e adicionei um hover padrão desse tipo de plataforma para trabalhar a irmersão da plataforma. 

  * Notas: Desevolver em grid é interessante, irei replica-lo para o próximo trilho que irei desenvolver. 

  ---faz bem práticar né.

            
          =========  TAREFA #04 - 05/11/23 ======>

Desenvolvendo os trilhos de seleção de título. 





         =============  TAREFA #03 - 31/10/23 Comeback =========> 

        Após um periodo afastado devido aos trabalhos da faculdade estou rotmando com projeto, irei finalizar os bottons e comecçar a desenvolver a barra de navegação.

-----UpDate 31/10/23

Finalizei o banner, e seus devidos button e comecei a desenvolver o
 <header nav> 

 Dica:: Construa a ideia primeiro sem se prender aos detalhes, cada elemento e seu devido lugar, após isso se volte ao detalhes. 

  * Foca sua atenção em um ponto de cada.  

Estou utilizando header para desenvolver toda a parte de navegação do menu.

----Update2

* Barra de navegação finalizada. Foi um desafio bem bacana pois pude trabalhar melhor com icons e li's ; aproveitei e dei um acabamento no banner, refinamento. 



        =============== TAFERA #02 - 13/10/23 =================>=>=>

 Os buttons não estavam me agradando, anteriomente tinha colocado como <a> como forma de acessar as "Mais informações", entretando após estudar um pouco ao longo do dia alterei para ambos serem um <button>. 

 * Assistir//Mais informações = {<button type="submit" class="#">} Encontrei a mesma prorpiedade do formulário. type="submit" - um botão que, ao ser clicado, submete o botão; Não adiciono um valor pois não é um formalário. 

* Utilizei um background-linear-gradient para montar a as vinhetas - e definindo o padding - [pegarvaloresdereferência.]
{
    linear-gradient( to bottom,
    rgba(0, 0, 0, 0.9) 5%,
    rgba(0, 0, 0, 0.2) 20%,
    rgba(0, 0, 0, 0.2) 80%,
    rgba(0, 0, 0, 0.8) 100%
    ),
    padding: 0.26rem 0.75rem 0 0.75rem;
}
            
             O que eu estava fazendo antes da correção ? 

Não tinha pensado na vinheta e a imagem estava ficando de forma estática e sem imersão e a forma que estava trabalhando com as imagens estava mais complexa que o necessário. 
======================================================================= 
* o background é de fato o título/anime/movie que está sendo apresentado.

* Importei o logo que será uma imagem fixa dentro do html e o bg no css (possuí variável).

===========================================================
Utilizando o  

    -webkit-text-stroke-width: 0.01rem;
    -webkit-text-stroke-color: black;

Para criar o contorno no Títilo - (arco) == Porém existe uma forma abreviada de utilizar e se obter o mesmo resultado. 

-webkit-text-stroke: 3px black ---- UPDATE

Para o resultado desejado, utilizei o atributo "text-shadow", por conta da sua versatiidade. 


    ========= TAFERA #01 - 12/10/23 =================>=>=>


    Montando toda a estrutura principal do site, analisando a imagem de referência e montando a ideia. 

* A minha ideia é ter uma plataforma dedicada ao anime One Piece, com suas temporadas, filmes, ovas e especiais. 

* Montar o banner de destaque da página.

Importei uma font do One Piece com o formato .ttf 
Ao invés de colocar no index, fiz o catch (captura) dentro do CSS --->->-> Leia o código para entender 

    Icon no head -->->-> 
    Através da tag <link rel="icon" type="image/png" href="">

  * Realizei a configuração padrão para exibir uma imagem em fullscreen dentro do CSS. 

  [Como será uma plataforma que terá muita repetição, estruturei breviamente as classes:]
  
  * Arcos (Nome da temporada) = .arco__ titulo /
                                 .arco__ logo (logo do anime )
    Descrição da arco = .arco__descricao.

  {Criei uma div para conter o logo do anime e o título do arco e realizar a organização dos itens.}
 
  * Filmes = .movie__ titulo / .movie__img
    Descrição dos filmes = .movie__descricao

  * Palavras destaque na descrição = .descricao__destq (estabeler padrão)
  
 
        Lista de FONTs do projeto: 
* Lato - GoogleFonts
* Gabarito - GoogleFonts
* OnePiece font - Internet/arquivo ttf



  



