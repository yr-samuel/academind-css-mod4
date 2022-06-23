### Multiplas classes e combinação de seletores

* É possível ter mais de uma classe aplicada para um mesmo elemento, a forma de fazer isso é passando o nome das classes separadas por um espaço em branco no atributo class, como por exemplo: *class="main-section highlighted"*.
    * Lembrando que se as duas ou mais classes lidarem com a mesma propriedade CSS, fica a definição da classe que tiver mais especificidade (quando se faz alguma combinação de selotores) ou pelas regras de ordem (vide cascata).

* Existe um certo tipo de combinação de seletores que diz que só será aplicado o estilo CSS se aquela classe, id ou atributo for de um elemento, id, atributo ou classe específica, como por exemplo: *a.active, .class1.class2, #id.class1, [role="switch"].btn*, no primeiro caso diz que o estilo CSS só vai ser aplicado a um elemento ancora que tiver a classe active, se não for exatamente isso, o estilo não é aplicado.