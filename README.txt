Luiz H. japecanga Dos Santos

O que foi implementado:
- `enums/FurColor.java`: criei o enum com os códigos e nomes de exibição pedidos, além do método `fromCode(int)` para localizar uma cor pelo código.
- `model/Cat.java`: implementei a classe `Cat` herdando de `Animal`, com os atributos extras pedidos, construtor, sobrescritas e sobrecargas de método.

Decisões tomadas:
- Segui o mesmo padrão usado em `TrainingLevel`, `Habitat`, `Animal` e `Dog`, para manter consistência no projeto.
- No construtor de `Cat`, o `habitat` e o valor de `isWild` são definidos com base em `isIndoor`, como orientado no enunciado.
- Usei `furColor.getDisplayName()` no `displayInfo()` para mostrar a cor de forma legível.

Como testei:
- Verifiquei se o enum possui as sete constantes, os getters e o `fromCode()`.
- Conferi se `Cat` compila com a superclasse `Animal`, sobrescreve `makeSound()`, `sleep()` e `displayInfo()`, e possui os overloads de `move()`.
- Se necessário, posso adicionar uma classe `Main` de teste para demonstrar a execução dos métodos.
