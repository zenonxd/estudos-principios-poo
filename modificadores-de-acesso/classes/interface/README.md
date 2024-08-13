# Interface

Uma classe abstrata pode ter atributos/métodos protected, atributos/métodos abstract.

Mas uma classe com Interface, é diferente! A gente só pode ter **definição de métodos.** Ela não terá atributos, nem definições de corpo de método.

Por exemplo, uma interface Avenger. O que a gente espera que uma classe que terá essa interface tenha?

Por fim, nos iremos à classe e implementaremos essa interface.

```java
public class HomemAranha extends SuperHeroi implements Avenger{}
```

**Não existe herança múltipla (múltiplos extends), mas podemos implementar diversas interfaces.**

Cabe destacar, que ao implementar uma interface a classe que deverá cumprir um "contrato". Ou seja, deverá implementar os métodos (que por padrão são abstratos).

\
