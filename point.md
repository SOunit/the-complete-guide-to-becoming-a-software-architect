# career

- `architecture` is after `sr.developer` and `team lead`

# select tech stack

- functionality
  - WebAPI
  - DesktopApp
  - etc.
- community
  - `stack overflow`
    - tag
    - keyword search
    - check question count
- popularity
  - `google trends`
    - search keyword
    - compare `react` and `angular`

# component architect

- layer for module

  - access only neighbor layer
  - hide detail into each layer

  - UI layer
  - BL(Business Logic) layer
  - DAL(Data Access Layer)

- interface for loose couple
  - `new is glue`
    - use `Interface`
    - use `DI`
      ```
        ICalculate calc = GetInstance();
        double result = calc.add(5,10);
      ```

# exception best practice

- catch if necessary

  - catch if you need some action
    - retry
    - rollback
    - etc.
  - if not leave logging to central exception handling mechanism

- use specific error class

  - if general, you may catch some error you didn't expect

- wrap smallest chunk of code with try/catch
