<h1>⭐️ Flex Box ⭐️</h1>

<h3>🔺 O Flexbox é um conjunto de propriedades que tem por objetivo organizar itens dentro de um elemento pai, normalmente chamado de container.</h3><br>

<h3>🔺 O primeiro passo para utilizar o Flexbox é definir a propriedade display do container com o valor flex.</h3><br>

<h3>🔺 A propriedade flex-direction deve ser aplicada ao container e define o eixo/fluxo de exibição em que os elementos serão organizados.</h3>


<p>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶 row (padrão): Os itens são organizados em forma de linha da esquerda para a direita;
        

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶 row-reverse: Os itens são organizados em forma exibição em linha da direita para a esquerda;
        

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶 column: Os itens são organizados em forma de colunas iniciando de cima para baixo;
        

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶 column-reverse: Os itens são organizados em forma de colunas iniciando de baixo para cima.
</p><br>
        



<h3>🔺 A propriedade flex-wrap aplicada ao container podemos alterar esse comportamento, fazendo com que ocorra a “quebra de linha” nos itens.</h3>
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶nowrap (padrão): Todos os itens serão dispostos em uma linha;</h4>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶wrap: Ocorrerá a quebra de linha e os itens mais à direita serão deslocados para a linha de baixo;</h4>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶wrap-reverse: Ocorrerá a quebra de linha e os itens mais à direita serão deslocados para a linha de cima;</h4><br><br>

<h3>🔺 Com o flex-flow podemos escrever as duas de forma simplificada</h3>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-flow: column wrap;</h4><br>

<h3>🔺 A propriedade justify-content define o alinhamento dos itens ao longo do eixo principal do container.</h3>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-start (padrão): Os itens são alinhados a partir do início do eixo principal;
          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-end: Os itens são alinhados a partir do fim do eixo principal;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶center: Os itens são alinhados ao centro do eixo principal;
          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶space-between: O primeiro item é deslocado para o início do eixo principal, o último é deslocado para o final do eixo principal e os demais são distribuídos uniformemente entre eles;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶space-around: Os itens são uniformementedistribuídos ao longo do eixo principal. Aqui, porém, são atribuídas margens iguais à esquerda e à direita (ou acima e abaixo, dependendo da direção do eixo principal). Por isso o primeiro e o último item não ficam “colados” nas bordas do container.</p><br>

<h3>🔺 A propriedade align-content define como as linhas são distribuídas ao longo do eixo transversal do container. </h3>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶stretch (padrão): As linhas são distribuídas uniformemente ao longo do eixo transversal, ocupando todo o espaço disponível;
          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-start: As linhas são distribuídas a partir do início do eixo transversal;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-end: As linhas são distribuídas a partir do fim do eixo transversal;
          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶center: As linhas são mantidas no centro do eixo transversal;
         
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶space-between: A primeira linha é deslocada para o início do eixo 
          transversal, a última é deslocada para o final do eixo transversal e as demais são distribuídas uniformemente entre eles;
          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶space-around: As linhas são uniformemente distribuídas ao longo do eixo transversal. Aqui, porém, são atribuídas margens iguais à esquerda e à direita (ou acima e abaixo, dependendo da direção do eixo transversal). Por isso a primeira e a última linha não ficam “coladas” nas bordas do container.</p><br>

<h3>🔺 Por padrão, os itens são distribuídos no container na ordem em que são inseridos no HTML. No entanto, essa ordem pode ser alterada por meio da propriedade order.</h3><br>

<h3>🔺 A propriedade flex-frow define a proporção com que um item deve crescer caso seja necessário. Por padrão seu valor é 0, o que indica que o item não deve crescer, e são aceitos apenas valores numéricos positivos.</h3>
 
        .item2{

        flex-grow:2;

        }<br>

<h3>🔺 A propriedade flex-shrink define a proporção com que um item deve encolher caso seja necessário. Por padrão seu valor é 0, o que indica que o item não deve encolher, e são aceitos apenas valores numéricos positivos.</h3>

         .item2{

        flex-shrink:2;

        }<br>


<h3>🔺 O flex-basis define o tamanho inicial que um item deve ter antes que o espaço ao seu redor seja distribuído. Ou seja, dependendo da direção do eixo principal (horizontal ou vertical), essa propriedade define a largura ou altura mínima do elemento antes que ele seja redimensionado por outras propriedades.</h3><br>

<h3>🔺  A propriedade align-self permite sobrescrever no item o comportamento que foi definido pela propriedade align-items.(tem prioridade no item)</h3><br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶auto (padrão): Respeita o comportamento definido no container por meio do align-items;
        
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶stretch: O item será esticado para preencher toda a dimensão do eixo transversal (altura ou largura);

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-start: O item é deslocado para o início do eixo transversal;
        
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶flex-end: O item é deslocado para o final do eixo transversal;
          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶center: O item é centralizado no eixo transversal;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔶baseline: O item é alinhado a partir da base da primeira linha de texto dos demais.





