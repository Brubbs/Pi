# Pi

Difícil - 3 – Pi: 

O programa é baseado em uma teoria de que em um círculo inscrito em um quadrado, temos a relação de a Área do círculo dividida pela Area do quadrado é igual ao número de pontos que cabem dentro do círculo dividido pelo número de pontos que cabem dentro do quadrado, resultando na fórmula de pi = 4*cont (pontos no círculo) / n (pontos no quadrado). Assim, na lógica do programa pegamos um círculo de diâmetro 1, inscrito em um quadrado de raio 1, assim ao pegarmos números aleatórios entre 0 e 1 para “x” e “y”, verificamos se eles são pontos dentro do círculo aplicando (x*x + y*y) < 1, se for verdade, esse ponto está dentro do círculo e o contador soma um. O n é o número total de pontos analisados e o número de pontos dentro do quadrado, uma vez que ao delimitarmos o de valor de o a 1, limitando para a área de dentro do quadrado. Como cabem infinitos pontos no círculo e no quadrado, quanto maior for “n”, obteremos um pi cada vez mais preciso. 

Nesse programa se é puxado a biblioteca “random” de python. 

Se é puxado a função “function”, que tem parâmetro “n”, que fornece quantas vezes a operação irá acontecer. Na função se é iniciado um contador “cont”, logo em seguida se tem um “for” que vai fazer o loop “n” vezes. No “for” as variáveis “x” e “y” vão receber números aleatórios de entre 0 e 1, utilizando –se de “random.uniform”, por “n” vezes. A cada valor recebido de “x” e “y”, esses valores são passados em um “if”, onde se (x*x +y*y) for menor que 1, será adicionado mais um ao contador. Depois na função, o valor de pi será calculado por 4 vezes cont, dividido por n, e a função retornará o valor de “pi”. 
