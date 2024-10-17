# codigo-de-alta-performance
Fazendo o nano course da Fiap de Código de Alta Performance

<h1>Capítulo 1: Listas lineares, pilhas e filas</h1>
<p>Listas lineares é chamado também de ordenação.</p>

<h3>Representação de informação em Sistemas computacionais</h3>
<p>Para explicar esta parte usaremos como exemplo a plaicação de previsão do tempo:</p>
<ul>
  <li>1º Partir dos calculos, que podem ser efeutados sem o uso de computadores, fazer a modelagem do problema para gerar algoritmo</li>
  <li>2º Obter medidas do mundo real como pressão, temperatura, umidade do ar etc. Para serem usados no processamento afim de obter informações sobre a probabilidade. Devemos escolher um tipo de dado mais adequado para representá-lo.</li>
</ul>

<p>O objetivo do estudo de estruturas de dados é fornecer novas formas de tratar dados</p>

<p>O que é um tipo de dado?
São valores que podem ser assumidos, operações que podem ser efetuadas
Por exemplo: Valores que representam quantidades contáveis de objetos, operações: soma, subtração, multiplicação, divisão e resto da divisão</p>

<p>Alguns tipos de dados são compreendidos diretamente  pelo processador, esses são os dados primitivos, os quais normalmente são: números inteiros com ou sem sinal, reais e caracteres.</p>
<p>Também temos o tipo conhecido como dados estruturados que são compostos internamente por dados primitivos, ou não. Como exemplo temos: vetores, matrizes </p>

<h4>Tipos abstratos de dados versus tipos "concretos" de dados</h4>
<p>No momento de modelar um problema(elaborar o algoritmo) é apenas necessário definir quais serão os tipos de dados que cada variàvel devera ser declarada, mesmo sem saber qual a linguagem de programação.</p>
<p>O número inteiro possui uma limitação quando definido pelo computador, pois é necessário ter uma quantidade máxima de dígitos binários(bits) para representar valores </p>
<p>Os tipos abstratos de dados (TAD) especificam as propriedades lógicas e matemáticas de um tipo de dados ou estrutura. Define um conjunto de valores e as operações que podem ser realizadas sobre esses valores, sem se preocupar com a implementação concreta. Um TAD não precisa levar em consideração como será o tipo de dado concreto que será usado no computador concentra-se na funcionalidade da lista.O foco está nas características e nos comportamentos que o tipo de dado deve ter, e não em como esses dados serão armazenados, com tempo, eficiência ou manipulados fisicamente. </p>

<h3>Organizando dados em estruturas de listas lineares</h3>
<p>Listas são muito usadas para lembrar de necessidades entre outros e para manter a organização. Em desenvolvimento de sistemas de computação também temos listas, por Exemplo:</p>
<ul>
  <li>Listas de arquivos a serem impressos</li>
  <li>Lista de solicitações de acesso para consulta de servidor de um banco de dados</li>
</ul>

<p> Precisamos definir uma ordem a fim de sermos justos com os usuários que solicitam algum serviço. Como nos casos acima usamos como regra atender o primeiro a solicitar</p>

<p>Uma lista linear é uma estrutura de dados que além de armazenar vários valores de elementos, impõe que a posição de cada elemento deve respeitar algum tipo de ordem. A característica princiapl de uma lista linear é o sentido de ordem unidirecional que a compôem, o critério para ordenação é bastante genérico, são definidos em função do problema</p>
<p>Exemplo de operações:</p>
<ul>
  <li></li>
</ul>
