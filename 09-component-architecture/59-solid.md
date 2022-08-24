# solid

- `Single responsibility`
- `Open / Close principle`
  - open to extend
  - close to modify
    - use inheritance
- `Liskov Substitution principle`

  - `subtype`(S) of `supertype`(T), object of `supertype`(T) can be replaced by `subtype`(S)

  ```
  Hero hero = new Hero();
  hero.run();
  ```

  ```
  Hero hero = new SuperHero();
  hero.run();
  ```

- `Interface Segregation`

  - create multiple focused interface than single multitask interface
    - big interface force to break single responsibility principle

- `Dependency Inversion Principle`
  - new is glue
    - make code tight couple
      - difficult to update
  - use `factory method`
