### Usar .classe ou #id?

* Classe (.class)
  * Primordialmente usadas para criar estilos CSS.
  * Reutilizáveis, pois você pode criar uma classe com uma regra CSS e colocar em qualquer elemento HTML.
  * É usada em conjunto com Javascript para fazer algumas coisas
  * É totalmente voltada para lógicas de CSS.
  * A primeira escolha para criar um estilo CSS deve ser uma classe, você cria um estilo totalmente com um contexto que você tem controle, diferente de estilizar diretamente um elemento pela tag, que pode e vai acabar afetando elementos que você não quer afetar.

* Id (#id)
  * Não deve haver mais de um elemento usando o mesmo id na mesma página.
  * Se tem certeza que um estilo vai afetar especificamente somente um elemento, usar Id talvez não seja um má ideia, mas deve ter certeza.
  * Outra coisa que é possível fazer com Id, é linkagem dentro da página, por exemplo, a gente passa uma id pra um elemento, e passamos esse mesmo id pro href de um elemento ancora, quando clicarmos nesse elemento ancora, o usuário vai ser levado até a parte da página que tem esse elemento com esse id.