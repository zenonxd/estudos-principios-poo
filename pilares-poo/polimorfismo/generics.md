# Generics

Nesse exemplo, criamos uma classe ImpressaoGenerics que irá possuir exatamente o que estava no Main (O array da Interface Trabalhador + o método de imprimir):

[![img\_13.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_13.png)](../../img\_13.png)

Ok, e se quiséssemos usar o imprimir para imprimir outras coisas sem ser um array de Trabalhadores?

Bom, nesse caso o método imprimir irá retornar um tipo `<T>` e como parâmetro, tabém receberá o mesmo.

Tipo `<T>` é em suma, um tipo genérico.

[![img\_14.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_14.png)](../../img\_14.png)

E assim, esse método será capaz de imprimir qualquer coisa.
