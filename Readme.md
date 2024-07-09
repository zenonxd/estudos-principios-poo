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

## Modificadores de Acesso - Atributos

Quais atributos fazem sentido ser publicos ou privados?

Foi o que falamos acima, volante e pedal é ok ser publico e acessado quando bem entender.
Já o airbag e motor, não...

Para os visíveis (publicos), utilizamos: ```public String volante```.

Para os privados (private), utilizamos: ```private String airbag```.

O private fará ser possível acessar os atributos somente dentro da própria classe.

## Modificadores de Acesso - Métodos

