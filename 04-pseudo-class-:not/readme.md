### :not Pseudo Classe

* Tenha preferência por usar sentenças afirmativas, para que o código CSS não tenha regras que não sejam legíveis e difíceis de dar manutenção.

* Mas, sobre a pseudo-classe :not, ela basicamente serve para negar um seletor, então basicamente ela diz assim: ó, estiliza tudo que não for compatível com a regra desse seletor aqui aplique e tal estilo.
  
    * Na regra abaixo esta sendo dito, aplique a cor vermelha para todos as tags \<a> que não tenham a classe .active.
      
          a:not(.active) {
            color: red;
          }

    * Na regra abaixo, esta sendo dito, aplique a cor azul para tudo que for filho de section mas não seja um parágrafo.
  
          section :not(p) {
            color: blue;
          }

    * Podemos fazer algumas regras mais complexas, como se o paragrafo não for filho de um artigo que é irmão direto de outro artigo, aplique a cor pink.

          p:not(article + article *) {
            color: pink
          }

    * Essa regra CSS acima, é basicamente o contrário de:

          article + article p {
            ...
          }

