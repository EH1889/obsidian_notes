In [[Programming]], modulus often represented using %, is the preferred method to use when building lambda calculous  functions.  

A simple example is to to consider if the consecutive numbers will sum to an Even Odd or Either value. When evaluating using [[Shell]] the syntax is as follows
$(( $1 % x)) where x is the modulus, thus.

```
#!/bin/sh

if [[ $(( $1 % 4 )) -eq 0 ]]
  then echo "Even"
elif [[ $(( $1 % 4 )) -eq 2 ]]
  then echo "Odd"
else
  echo "Either"
fi
```


Note:
If x is smaller than the number being evaluated the function will always evaluate to the number as it will be a remainder of itself. 

To run the function in memory use expr, for example

expr 3 % 6