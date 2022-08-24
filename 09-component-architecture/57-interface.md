# interface

# benefit of interface

- decouple code

# new is glue

- new make `tight couple code`

# tight couple code sample

```
Calculator calc = new Calculator();
double result = calc.add(5,2);
```

# loose couple code sample

```
ICalculator calc = GetInstance();
double result = calc.add(5,2);
```

- use `dependency injection`
- no tight couple
- can change class
- only interface is tight coupled
