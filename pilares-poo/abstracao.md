# Abstração

Basicamente, seria esconder/exibir dados e comportamentos.

Isso é importante, pois é comum a gente esconder detalhes dos objetos, para facilitar seu uso. Uma TV, por exemplo, é muito complexa, quase ninguem sabe construir uma TV. Mas ela é entregue para você com uma interface simples de uso.

Para fazermos isso, basta criarmos métodos de utilização pro produto. No caso da TV, seria criar métodos de aumentarVolume, diminuirVolume, trocarCanal...

Ah, nesses métodos a gente sempre trabalha com o atributo, a gente vai usar o "this", para EVIDENCIAR que é o atributo da classe! Exemplo:

```java
public void trocarCanal(int novoCanal) {
    this.canal = novoCanal;
    // usando o this para referenciar ao atributo da classe, e trocando seu valor para o que
    // está no parâmetro.
}
```
