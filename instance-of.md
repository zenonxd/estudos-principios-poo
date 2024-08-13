# Instance Of

Imagine um cenário, onde a gente precise pegar esse Array de super herói e chamar algum método que irá ver se o super herói é suportado pelo jogo.

Criamos um método que retornará um void e passaremos como parametro um Array de SuperHeroi.

Mas e para validarmos esse parametro e conhecer o seu tipo? (se é um HomemAranha ou HomemDeFerro).

Para descobrirmos o tipo concreto de uma super classe, usaremos InstanceOf.

```
static void validar(SuperHeroi[] superHerois) {
    //Verifica se o objeto super-heroi na posição 0 é uma instância do objeto HomemAranha
    if (superHerois[0] instanceof HomemAranha) {
        System.out.println("Lógica de validação do Homem Aranha");
    }
}
```
