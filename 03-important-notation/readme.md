### Notação !important.

* Basicamente essa notação quando for usada num estilo CSS, ela faŕa com que esse estilo seja aplicado e irá passar por cima de qualquer especificidade e também de qualquer outro seletor que esteja aplicando esse mesmo estilo independente da ordem.

* No geral, você NÃO DEVE usar o !important, na maioria dos casos não é a melhor opção.

* Ok, em geral não deve ser usado, mas onde então devemos usar? Bom, em alguns casos específicos como quando estamos usando alguma biblioteca externa e essa biblioteca não nos dá o controle para alterar o CSS dos elementos dela, esse seria um ótimo caso onde usar o !important não é uma má ideia.

      {
        border: 1px solid #ccc !important;
      }