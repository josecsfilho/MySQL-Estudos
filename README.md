# MySQL-Estudos


Começamos conhecendo a história do SQL e do MySQL. Em seguida, recuperamos o ambiente de trabalho e quem ainda não tinha o MySQL no computador aproveitou o material do curso introdutório para aprender como fazer essa instalação. Depois, recuperamos a base de dados "sucos_vendas" e exploramos o esquema de tabelas contido nesse banco, analisando seus conteúdos e suas relações.

Com esse conhecimento em mãos, partimos para as consultas. A princípio, realizamos seleções básicas, revisando conceitos do curso de Introdução ao SQL com MySQL, como a implementação de filtros simples. Depois, aprendemos sobre consultas condicionais, nas quais utilizamos operações lógicas, como maior, menor, maior ou igual, menor ou igual, AND, OR e IN, que significa "dentro de um determinado conjunto".

Entendemos a estrutura do LIKE, que é um modo especial para selecionar um conjunto específico de caracteres dentro dos campos, e estudamos o DISTINCT, um comando que restringe a saída, não permitindo que dados repetidos apareçam no retorno da consulta SQL. Ainda nesse âmbito, aprendemos a limitar as seleções (com LIMIT), tendo então a opção de não visualizar todos os registros, somente uma parcela em particular que nos interesse.

Ver os dados de forma ordenada (seja alfabeticamente ou por outro indicador) é imprescindível e, sem esse aspecto, o SQL não faria muito sentido. Nesse curso, aprendemos como efetuar a ordenação dos registros por meio ORDER BY, usando critérios mistos e especificando a direção em que as informações devem aparecer (de forma ascendente ou descendente).

Outra cláusula importante que estudamos é o GROUP BY, que nos permite agrupar dados — no caso de campos numéricos, aplicando fórmulas de soma, máximo ou mínimo. Para a elaboração de relatórios, o GROUP BY é um comando marcante.

Também passamos pela cláusula HAVING que, apesar de pouco usada no dia a dia, é bastante útil por possibilitar o uso de um dado numérico agrupado dentro de uma condição de filtro. Ademais, vimos o CASE (acompanhado do WHEN), uma ótima ferramenta para classificação. Com essa expressão, podemos avaliar dados numéricos, por exemplo, e determinar o que aparecerá na saída.

Em seguida, nos aprofundamos nos diversos tipos de JOIN, comandos que juntam tabelas em um único SELECT. Descobrimos que, dependendo do tipo usado, obtemos resultados bem diferentes. Depois, falamos um pouco sobre o UNION, que permite unir duas consultas em uma só. Vimos as distinções entre UNION e UNION ALL e focamos nas peculiaridades desse comando: é preciso que as tabelas em questão tenham o mesmo número de campos e que seus tipos coincidam.

Estudamos as subconsultas (ou seja, consultas dentro de outras consultas) e partindo desse conceito também aprendemos sobre as views no SQL.

Depois, estudamos as funções. Neste tópico, nos aprofundamos nas funções de string, que manipulam textos. Também vimos as funções de data, que permitem a extração de informações como dia ou hora, bem com a soma e a subtração de datas. Checamos as funções matemáticas, com as quais podemos fazer operações complexas ou efetuar, por exemplo, o arredondamento de valores. E, por fim, falamos das funções de conversão, responsáveis por converter os tipos dos campos. Às vezes, durante uma consulta SQL, é fundamental fazer essas conversões.
