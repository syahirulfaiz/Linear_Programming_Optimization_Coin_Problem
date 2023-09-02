# Linear Programming Optimization - Coin Problem #
A Linear Programming task where we have a goal to maximize a specific coins combination, provided by several contraint(s)


## Decision Variable ##

Pennies, Nickels, Dimes, Quarteers, Dollars

## Maximize ##

0.01 \* Pennies + 0.05 \* Nickels + 0.1 \* Dimes + 0.25 \* Quarters + 1 \* Dollars

## Contraints ##

Cu : 0.06 \* Pennies + 3.8 \* Nickels + 2.1 \* Dimes + 5.2 \* Quarters + 7.2 \* Dollars <= 1000 <br/>
Ni : 1.2 \* Nickels + 0.2 \* Dimes + 0.5 \* Quarters + 0.02\* Dollars <= 50<br/>
Zi : 2.4 \* Pennies + 0.5 \* Dollars <= 50<br/>
Mn : 0.3 \* Dollars <= 50<br/>

Pennies, Nickel, Dimes, Quarters, Dollars $\in {Z}^{+}_0$
