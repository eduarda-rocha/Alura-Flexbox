# Posicionamentos na tela

## De Desktop para Mobile

* Para mobile devemos colocar um elemento em baixo do outro, é a melhor forma de ocupar todo o espaço para melhorar a usabilidade no celular.

* Para fazer isso podemos colocar a propriedade `flex-direction: column;`, que faz com que os elementos fiquem um em baixo do outro. Esse é o aspecto mais importante da responsividade do flexbox.

## Flex container e flex items

* Quando colocamos `display: flex` em um elemento, o navegador passa a considerar esse elemento como um flex container, ou seja, cria todo aquele comportamento que vimos anteriormente no curso, os filhos ficam um do lado do outro e podemos aplicar propriedades para espaçá-los.

* Os filhos de um flex container por sua vez também ganham um nome, são chamados de flex items.

* Quando utilizamos flexbox temos que ficar atentos em quem colocamos as propriedades de espaçamento e distribuição do flex. Por exemplo, existem algumas propriedades que devem ser aplicadas à flex container e outras que devem ser aplicadas nos flex items. Exemplo: 

    ![Exemplo](https://i.imgur.com/mThvRZq.png)

## Propriedades do flex container e dos flex items

* Não há necessidade de gravar pois há essa informação em vários sites.

* flex container:
    * `display: flex`
    * `flex-direction`
    * `justify-content`
    * `flex-wrap`
    * `flex-flow`
    * `align-items`
    * `align-content`

* flex item:
    * `order`
    * `flex-grow`
    * `flex-shrink`
    * `flex-basis`
    * `flex`
    * `align-self`