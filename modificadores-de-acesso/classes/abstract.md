# Abstract

Se a classe SuperHeroi for abstrata, nós poderiamos ir no Main e criar simplesmente um:

```
new SuperHeroi("meu traje", new String[] {"contar piada"});
```

Ou seja, uma instância de SuperHeroi sem definir um nome específico, nem nada do tipo. A partir do momento que definimos a classe pai como ‘Abstract’, não é mais possível criar uma instância da classe pai sem definir um nome a ela.

**Bom, mas os métodos dessa classe também podem ser abstratos.**

E isso significa que esse método ficará vazio! Sem corpo, sem definição, sem nenhum bloco de comando. Somente com o seu retorno e parâmetro, assim:

```
public abstract void usarSuperPoder(int index);
```

**E o resultado disso?**

Bom, o que acontece, é que as classes, com esse método que se tornou abstrato implementado, vai precisar que a gente (de forma obrigatória), defina o seu corpo e os seus blocos de comando (o que de fato ele irá fazer).

Usaremos o @Override e implementaremos o que a gente quer.
