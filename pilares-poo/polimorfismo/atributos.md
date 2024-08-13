# Atributos

F**alamos de atributos em métodos, mas e nos atributos?**

Bom, aqui criamos uma classe Empregado que possui um atributo nome:

[![img\_15.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_15.png)](../../img\_15.png)

E exentederemos essa classe na Programador, mas atribuiremos um valor de "Programador":

[![img\_16.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_16.png)](../../img\_16.png)

Ao instanciarmos o Emprego e Programador chamando o ".nome", o que será exibido?

[![img\_17.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_17.png)](../../img\_17.png)

Mas se o programador for instanciado como Empregado, será exibido "Empregado" ao invés de "Programador".

Por fim, para que a gente saiba o que será exibido, é só olharmos o tipo da variável. Sempre será a super classe que será exibida.
