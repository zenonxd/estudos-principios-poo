# Princípios de POO

# Pilares de POO
![img.png](img.png)

Seguindo esses quatro pilares, será possivel obter um projeto orientado à objetos.
<hr>

## Encapsulamento

Seu objetivo é esconder detalhes internos, expondo a interface facilitada do objeto. Por exemplo:
![img_1.png](img_1.png)

Imagine um carro. O motorista que é usuário do carro, ele pode interagir com o carro.

Mas ele interage somente com as interfaces disponíveis no carro (volante, pedais, o painel). Então,
ele não precisa necessariamente saber como é o funcionamento do motor, dos airbags.. isso são detalhes
ocultos, ou... **encapsulados**.

Não é bacana, portanto, deixamos todos os objetos da nossa clase exposto. É possível que ao fazer isso,
o cliente não saiba/consiga usar o produto da forma correta (e até mesmo, segura).

O AirBag, por exemplo, não deve ser ativado pelo usuário quando bem quiser... e ainda entra os
modificadores de acesso.
<hr>

## Modificadores de Acesso - Atributos

Quais atributos fazem sentido ser publicos ou privados?

Foi o que falamos acima, volante e pedal é ok ser publico e acessado quando bem entender.
Já o airbag e motor, não...

Para os visíveis (publicos), utilizamos: ```public String volante```.

Para os privados (private), utilizamos: ```private String airbag```.

O private fará ser possível acessar os atributos somente dentro da própria classe.

## Modificadores de Acesso - Métodos

Também podemos usar esses modificadores nos métodos.

Em suma, se quiser esconder um método é só declarar o modificador private!
<hr>

## Getters e Setters

Dificilmente teremos atributos públicos. A maioria sempre será private e acessaremos os mesmos com
Getters e Setters.

Eles nos permitem buscar o atributo em questão (get) e settar algum valor neles (setter).
<hr>

## Modificadores de Acesso - Classes

As classes também podem ser modificadas. Porém só possuem 2 modificadores.

O public que é o padrão.

Mas também tem o “default”. Ou seja, vai ficar só ```class Carro {}```.
<hr>

## Encapsulamento no Construtor

O Construtor até pode ser private, o problema é que não será possivel instanciá-lo em outras classes.

Vale lembrar que o Construtor é onde inicializamos os atributos. Então é o local onde colocaremos os
valores que desejarmos.

![img_2.png](img_2.png)
<hr>

## Abstração

Basicamente, seria esconder/exibir dados e comportamentos.

Isso é importante, pois é comum a gente esconder detalhes dos objetos, para facilitar seu uso. Uma TV,
por exemplo, é muito complexa, quase ninguem sabe construir uma TV. Mas ela é entregue pra você com
uma interface simples de uso.

Para fazermos isso, basta criarmos métodos de utilização pro produto.
No caso da TV, seria criar métodos de aumentarVolume, diminuirVolume, trocarCanal... 

Ah, nesses métodos a gente sempre trabalha com o atributo, a gente vai usar o "this", para EVIDENCIAR
que é o atributo da classe! Exemplo:
```java
public void trocarCanal(int novoCanal) {
    this.canal = novoCanal;
    // usando o this para referenciar ao atributo da classe, e trocando seu valor para o que
    // está no parâmetro.
}
```

