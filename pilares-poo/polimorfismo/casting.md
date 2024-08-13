# Casting

Agora, uma única coisa. Como nós declaramos um cozinho por exemplo através da Interface, caso exista dentro da classe Cozinheiro outro método:

[![img\_7.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_7.png)](../../img\_7.png)

A variável no Main não será apta a enxergar esse método criado. O que é específico da classe Cozinheiro só sera possível ver se intanciarmos ela.

Para isso, podemos usar um InstanceOf. No exemplo em questão, colocamos os 3 trabalhadores instanciados dentro de uma array:

[![img\_8.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_8.png)](../../img\_8.png)

E faremos um método para percorrer esse array.

[![img\_9.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_9.png)](../../img\_9.png)

E caso essa varíavel dentro do for seja uma InstanceOf Cozinheiro, aí sim poderá ser visualizado o método da classe.
