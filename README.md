 # Flexbox CSS

O Flexbox CSS é um módulo de layout poderoso que foi introduzido no CSS3 e oferece uma abordagem flexível para organizar e alinhar elementos em um container. Ele foi projetado para facilitar a criação de layouts responsivos e adaptáveis, permitindo que você controle o posicionamento e o comportamento dos itens em um design fluido.

O Flexbox funciona com um sistema bidimensional, onde você tem um elemento container (ou flex container) que envolve os itens que deseja organizar. Ao definir o container como um flex container, você ativa o Flexbox e ganha acesso a várias propriedades que controlam a disposição dos itens.

Para começar a utilizar o Flexbox, você precisa definir o elemento container como um flex container, aplicando a propriedade `display: flex;`. Isso informa ao navegador que o container usará o Flexbox para organizar seu conteúdo. A partir desse momento, você pode usar uma série de propriedades do Flexbox para ajustar o layout dos itens.

Uma das principais propriedades do Flexbox é o `flex-direction`, que controla a direção na qual os itens são dispostos dentro do container. Por padrão, a direção é definida como `row`, o que significa que os itens são alinhados em uma única linha horizontal. No entanto, você pode alterar para `column` para alinhar os itens em uma única coluna vertical. Além disso, existem os valores `row-reverse` e `column-reverse`, que invertem a ordem dos itens.

Outra propriedade importante é o `justify-content`, que define como os itens são distribuídos ao longo do eixo principal do container. Com essa propriedade, você pode alinhar os itens no início do container (`flex-start`), no final (`flex-end`), centralizados (`center`), distribuídos igualmente com espaçamento entre eles (`space-between`) ou distribuídos com espaçamento igual ao redor deles (`space-around`).

O alinhamento vertical dos itens é controlado pela propriedade `align-items`. Com essa propriedade, você pode definir se os itens devem ser esticados para preencher o container (`stretch`), alinhados no início (`flex-start`), alinhados no final (`flex-end`), centralizados verticalmente (`center`) ou alinhados com base nas linhas de base (`baseline`) dos itens.

Caso seu container possua várias linhas de itens, você pode usar a propriedade `flex-wrap` para controlar o comportamento de quebra dos itens. O valor padrão é `nowrap`, o que significa que os itens permanecerão em uma única linha. No entanto, você pode definir `wrap` para permitir que os itens quebrem em várias linhas quando não houver espaço suficiente. Além disso, o valor `wrap-reverse` fará com que a quebra ocorra em ordem reversa.

Outras propriedades, como `align-content` e `order`, também estão disponíveis no Flexbox e permitem um controle mais detalhado do layout dos itens.

Uma das grandes vantagens do Flexbox é sua capacidade de criar layouts responsivos de maneira eficiente. Combinado com media queries, você pode ajustar as propriedades do Flexbox com base no tamanho da tela, garantindo que seu layout seja adaptável a diferentes dispositivos.

            Flexbox CSS
                |
                |
     _______________________________
    |            |                  |
    |   Flex     |    Flex Container |
    |   Item     |                  |
    |____________|__________________|
                |
                |
       _____________________
      |           |         |
      |  Flex     |   Flex  |
      |  Item     |   Container |
      |___________|_________|
                |
                |
         _______________
        |               |
        |   Flexbox     |
        |   Properties  |
        |_______________|
                |
                |
     ______________________________
    |          |          |         |
    |  Flex    |   Flex   |  Flex   |
    |  Item    |   Item   |  Item   |
    |  Order   |   Grow   |  Shrink |
    |          |          |_________|
    |__________|__________________|
                |
                |
     ______________________________
    |          |          |         |
    |   Flex   |   Flex   |   Flex  |
    |   Item   |   Item   |   Item  |
    |   Basis  |   Align  |   Wrap  |
    |          |   Items  |   and   |
    |__________|__________|_________|
                |
                |
          ___________________
         |                   |
         |   Flex Container  |
         |   Properties      |
         |___________________|
                |
                |
     _______________________________
    |          |          |         |
    |  Flex    |   Flex   |  Flex   |
    |  Direction|  Justify |  Align  |
    |          |  Content |  Self   |
    |__________|__________|_________|
.
