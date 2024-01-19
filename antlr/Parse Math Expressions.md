# Parse Math Expressions

Let's parse math expressions like this:

```
4 + (7 - 8) / 3 * 5 + 2
```

And Calculate the result!

## TODO List

### Phase 1 - Simple Integer Calculator

- Write an antlr grammar for any math expression of integers and simple operators (+-*/)
- Calculate the value of an expression
- Print a parsed expression with parenthesis to disambiguate chained operations, obeying the order of operations

### Phase 2 - Decimal Calculator

- Expand the grammar to include exponent (^)
- Expand the grammar to include decimals
- Expand the grammar to include negative numbers
- Expand the grammar to include other functions, e.g. mod, sqrt, log

### Phase 3 - Algebraic Solver

- Expand the grammar to allow variables
- Expand the grammar to allow equations
- Expand the grammar to allow for multiple lines of expressions/equations
- Solve for systems of equations

### Phase 4 - Complex Variable Sovler

- Expand the grammar to include constants, e.g. e,pi,i
- Solve for Complex expressions/equations