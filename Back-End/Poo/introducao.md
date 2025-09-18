## **Introdução a Programação Orientada a Objetos (POO)**

- Surge como uma variação da linguagem estuturada, a fim de representar algo tangível no mundo real. Dito isso, surge o termo "objeto", que é algo representado no mundo real só que dentro de um programa.


### O que são **Classes e Objetos?**

- Uma classe é nada mais que um molde de um objeto que contém funções, características e comportamentos de algo real. Um exemplo seria a Classe Pessoa, onde teria os atributos como pernas, olhos, boca, nariz, etc.. Só que essa classe pessoa pode ter vários objetos de formas diferentes, ou seja, existem pessoas de diferentes formas e características, mas todas elas pertencem a Classe Pessoa.





### As principais características da POO.

- **Encapsulamento:** É usado para omitir atributos e métodos (características e comportamentos) de uma classe a fim de esconder detalhes internos e para segurança também. Permitindo o acesso desses detalhes apenas por métodos específicos como getters e setters. 

- **Herança:** Como o próprio nome já diz, herança é usado quando se deseja herdar atributos e métodos de alguma outra classe. Em um cenário com uma Classe Cachorro e uma Classe Poodle, a classe Poodle herda da classe Cachorro já que o Poodle é um cachorro. Podemos dizer que há uma relação entre a superclasse e a classe filha.

- **Interfaces:** Uma interface define um conjunto de métodos que uma classe deve implementar, sem fornecer a implementação desses métodos. Ela funciona como um contrato: qualquer classe que implemente a interface é obrigada a fornecer uma implementação para todos os métodos definidos nela.
Diferente de classes comuns, interfaces não possuem atributos nem métodos com corpo (embora em linguagens como Java 8+ seja possível ter métodos com implementação padrão).
Elas são úteis quando duas ou mais classes compartilham comportamentos em comum, mas não têm uma relação de herança direta. Assim, a interface permite que diferentes classes adotem o mesmo conjunto de comportamentos, mesmo que não estejam na mesma hierarquia.

- **Polimorfismo:** Polimorfismo é um princípio da programação orientada a objetos que permite que um mesmo método tenha comportamentos diferentes, dependendo do objeto que o utiliza.
Ele possibilita que classes diferentes respondam de forma distinta a uma mesma mensagem (método), o que torna o código mais flexível e reutilizável.
Dizemos que o polimorfismo promove a ideia de que objetos de diferentes classes podem ser tratados de forma uniforme, desde que compartilhem uma interface comum ou herança.

