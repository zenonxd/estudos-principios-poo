# Herança

Seria o reuso. A ideia é evitarmos desperdício.

Ou seja, vamos centralizar a lógica em um lugar e torná-la acessível.

[![img\_3.png](https://github.com/zenonxd/estudos-principios-poo/raw/main/img\_3.png)](../img\_3.png)

Nós teremos uma classe pai (chamada de super classe), e ela irá possuir atributos e métodos a serem herdados por outras classes (classes filhas).

Vamos imaginar um exemplo de super-heróis. Em um pacote podemos ter uma classe: HomemAranha, Tempestade e HomemDeFerro.

Não é correto dentro do Main nós criarmos diversos métodos passando um super-heroi para cada um.

O correto, portanto, seria criar uma super classe denominada SuperHerói, contendo nela tudo o que um super-herói irá fazer.

Atributos padronizados, um método e até mesmo um construtor para iniciar um novo super-herói.

#### Beleza, a super classe foi criada. E pra aplicar ela a outras classes filha?



A gente simplesmente vai até a classe filha, HomemDeFerro, por exemplo, e usa a palavra **extends**.

Essa classe filha agora irá herdar e ser uma subclasse da outra. Vai herdar todos os atributos, métodos e construtores da superclasse.
