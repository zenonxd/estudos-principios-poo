# Encapsulamento

Seu objetivo é esconder detalhes internos, expondo a interface facilitada do objeto. Por exemplo:

[![img\_1.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_1.png)](../../img\_1.png)

Imagine um carro. O motorista que é usuário do carro, ele pode interagir com o carro.

Mas ele interage somente com as interfaces disponíveis no carro (volante, pedais, o painel). Então, ele não precisa necessariamente saber como é o funcionamento do motor, dos airbags.. isso são detalhes ocultos, ou... **encapsulados**.

Não é bacana, portanto, deixarmos todos os objetos da nossa classe expostos. Ao fazermos isso, é possível que o cliente não saiba/consiga usar o produto da forma correta (e até mesmo, segura).

O Airbag, por exemplo, não deve ser ativado pelo usuário quando bem quiser... e ainda entra os modificadores de acesso.
