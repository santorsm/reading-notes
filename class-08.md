# Operators and Loops

## Comparison operators

- `==` : is equal to
  - compares two numbers to see of they are the same
-`!=` : is not equal to
  - compares two numbers to see of they are the *not* the same
  - preferable to use the strict method
- `===`: strict equal to
  - compares two values to check **both** *data* *typ* and *value* are the same
- `!==`: strict not equal to
  - compares two values to check **both** *data* *typ* and *value* are *not* the same

## Logical operators
- allow you to compare more than one comparson operator
- Do exp 1 & exp 2 both evaluate to true?
- ((5 < 2) && (2 >= 3))
- `&&`: Logical AND
  - tests for more than 1 condition
- `||`: Logical OR
  - Tests at least one condition
- `!` Logical NOT:
  - takes singel value and inverts it

## Loops
- `FOR`: run code for a specific # of times
  - usually acounter
- `WHILE`: when you don't know how many times to run
  - can be something other than a counter
  - code will continue to loop for as long as the condition is true
- `DO WHILE`: will always run the statements inside the curly braces at least once
  - even if conditions evaluate to `false`

  for (var i = 0; i < 10; i++) {
    document.write(i);
  }
    - initialization: var i = 0
    - condition: i < 10
    - update: i++

  while (i < 10) {
    msg += i + ' x 5 = ' + (i * 5) + '<br />';
    i++;
  }
    - `+=` :shorthand for writing: msg =msg + 'newmsg'