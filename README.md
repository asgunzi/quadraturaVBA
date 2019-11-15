Quadratura do retângulo

<p>Aqui, uma macro que lida com o problema da “quadratura do retângulo”.</p>

<p>Dado um retângulo, digamos de tamanho 11 x 10, como eu
decomponho a mesma no menor número de quadrados menores?</p>


![](https://ideiasesquecidas.files.wordpress.com/2019/11/quadrado_11_10.jpg)

<p>A macro utiliza um algoritmo recursivo. Basicamente, esta vai testando todas as combinações possíveis em duas dimensões, até chegar ao final, e compara o número de quadrados gerados. É o chamado método da força-bruta.</p>

<p>Mesmo incluindo alguns truques, como eliminando quem tem
mais quadrados que o mínimo até então, o algoritmo continua sendo força bruta –
ou seja, demora muito quando aumenta o tamanho do problema.</p>

<p>Outro exemplo, um retângulo 13 x 11.</p>

![](https://ideiasesquecidas.files.wordpress.com/2019/11/quadrado_13_11.jpg)

<p>Uma utilidade possível é encaixar produtos em pallets, ou
conjugar cargas em carregamentos, utilizando métodos adaptados.</p>

<p>Há um problema similar, porém com uma restrição muito mais forte: todos os quadrados menores devem ter<strong> tamanho diferente.</strong></p>

<p>Esta restrição é tão forte que a maioria dos retângulos não
vai ter solução. Porém, algumas que as têm geram resultados muito bonitos, como
o seguinte (retângulo 33 x 32). </p>


![](https://ideiasesquecidas.files.wordpress.com/2019/11/quadradosdiferentes.jpg)

<p>Houve uma série de matemáticos que estudou este problema,
chegando em soluções bem legais (porém, muito mais matemáticas que
computacionais). </p>

<p>Uma história desses é mostrada no livro “Mania de matemática”, de Ian Stewart.</p>


