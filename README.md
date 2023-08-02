<!-- Título -->
# Introdução

***Conteúdo da Aula:***

Um vetor é uma série ou lista de valores presentes na memória do computador, de mesmo nome e tipo de dado, mas diferenciados por números especiais chamados índices.

Normalmente, todos os valores de um vetor têm algo em comum.

Por exemplo:

* Eles podem representar uma lista de identificação de funcionários;
* Uma lista de preços dos itens de uma loja;
* Uma lista de nomes dos seus melhores amigos.

Pegando como exemplo a lista com os nomes de seus melhores amigos: nosso *array* ou vetor provavelmente deverá ser do tipo `char`.

Cada posição de nosso vetor – já que um vetor é segmentado – receberá um índice, do tipo `inteiro`, de acordo com a sua posição.

Se tivéssemos um vetor com os nomes **“José”**, **“João”** e **“Paulo”** respectivamente, eles teriam os índices `0`, `1` e `2`.

É importante sempre se lembrar:

* No **C** e na grande maioria das linguagens de programação, a contagem começa do número `0`, e não do `1`.
* O interessante é que não precisaremos criar três variáveis distintas para guardar o nome de cada um dos três amigos citados anteriormente: nós podemos centralizar o armazenamento destas informações em um único lugar, o que torna o código mais legível.

Em **C**, para criarmos vetores, temos a seguinte sintaxe:

```c
<tipo de dado do vetor> <nome do vetor>[<quantidade de posições>]
```

Se quiséssemos declarar um vetor de inteiros de três posições chamado `meuVetor`, teríamos de o declarar da seguinte maneira:

```c
int meuVetor[3];
```

Se quiséssemos colocar os números `25`, `36` e `45` dentro de nosso vetor, por exemplo, poderíamos fazer da seguinte maneira:

```c
meuVetor[0] = 25;
meuVetor[1] = 36;
meuVetor[2] = 45;
```

Veja:

* Nós colocamos os três números dentro da mesma **“variável”**: o nosso vetor `meuVetor`.
* Porém, cada número ficará atrelado a um índice diferente, índice este iniciado em `0`.
* Veja também que para acessarmos cada uma das posições desejadas, nós a identificamos chamando o nosso vetor e identificando a posição que se deseja acessar através do índice, o indicando entre colchetes.
* O mesmo vale se quisermos somente ler uma posição do vetor.

![Exemplo.](https://d2v0x26thbzlwf.cloudfront.net/prod/14/img/rId208fd0nex5.88n.gif)

Todos os elementos estão no mesmo vetor – no caso, o vetor `meuVetor` - mas cada elemento possui um índice distinto, que o identifica, começando pelo primeiro elemento.

Os índices de qualquer vetor são sempre valores inteiros.

Com relação à memória, podemos imaginar que os números que acabamos de colocar dentro de nosso vetor estariam dispostos da seguinte maneira:

![Exemplo.](https://d2v0x26thbzlwf.cloudfront.net/prod/14/img/rId213dbcq1gm.ey3.png)

Os valores que foram colocados dentro de um vetor podem ser utilizados normalmente para fazer operações aritméticas, para operações lógicas e relacionais e todas as outras, como se cada posição fosse de fato uma variável distinta.

Porém, sempre será necessário se especificar o índice do elemento a ser utilizado nestes casos.

Outro ponto que você precisa se atentar é com relação ao tamanho do vetor:

* Se você tentar acessar uma posição que esteja além do tamanho do vetor, ocorrerá um erro de execução de seu algoritmo.
* Por exemplo, é impossível acessar a posição `10` de um vetor com `10` posições...
* Por que não é possível?
* Porque um vetor que tem `10` posições possui os índices de `0` até `9` (não se esqueça de que no **C** a primeira posição é identificada pelo índice `0`!) e o índice `10` é inválido neste cenário.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-int-est-dad-vet-arr-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-int-est-dad-vet-arr-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-int-est-dad-vet-arr-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-int-est-dad-vet-arr-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-int-est-dad-vet-arr-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-int-est-dad-vet-arr-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
