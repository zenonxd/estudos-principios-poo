# Polimorfismo

[![img\_4.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_4.png)](../../img\_4.png)

O verbo trabalhar, por exemplo. Todo trabalhador trabalha. Mas... e se for um programador? Qual o trabalho dele?

Ou seja, dependendo de onde o método for chamado, ele vai se comportar de forma diferente. Terá várias formas.

Cabe destacar que usamos o polimorfismo utilizando da herança. Isso tudo nos permite o reuso do código, proporcionando uma melhor usabilidade, etc.

Seguindo o exemplo de trabalho, criaremos uma interface Trabalhador.

[![img\_5.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_5.png)](../../img\_5.png)

E criaremos outras classes para implementar essa interface e cumprir esse "contrato". Essas classes podem ser: Médico, Cozinheiro, Programador..

E no Main ao invés de instanciarmos a clase criada, nós iremos referenciar a interface.

[![img\_6.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_6.png)](../../img\_6.png)

E elas se comportarão de forma diferente, mesmo com a mesma funcionalidade em comum (ser da interface Trabalhador).
