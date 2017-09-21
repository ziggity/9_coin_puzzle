# 9 Coin puzzle

####

#### By **Zach Beecher**

## Description

Nine-coin problem

Solution to the balance puzzle for 9 coins in 2 weighings, where the odd coin is lighter than the others – if the odd coin were heavier than the others, the upper two branches in each weighing decision are swapped
A well-known example has nine (or fewer) items, say coins (or balls), that are identical in weight save for one, which in this example is lighter than the others—a counterfeit (an oddball). The difference is only perceptible by weighing them on scale—but only the coins themselves can be weighed. Is it possible to isolate the counterfeit coin with only two weighings?

Solution
To find a solution, we first consider the maximum number of items from which one can find the lighter one in just one weighing. The maximum number possible is three. To find the lighter one we can compare any two coins, leaving the third out. If the two coins tested weigh the same, then the lighter coin must be one of those not on the balance. Otherwise, it is the one indicated as lighter by the balance.

Now, imagine the nine coins in three stacks of three coins each. In one move we can find which of the three stacks is lighter (i.e. the one containing the lighter coin). It then takes only one more move to identify the light coin from within that lighter stack. So in two weighings we can find a single light coin from a set

By extension, it would take only three weighings to find the odd light coin among 27 coins, and four weighings to find it from 81 coins.

* Solution to the balance puzzle for 9 coins in 2 weighings, where the odd coin is lighter than the others – if the odd coin were heavier than the others, the upper two branches in each weighing decision are swapped

## Technologies Used

* JavaScript
* jQuery
* CSS
* HTML
* Bootstrap

### License

Copyright (c) 2017 **Zach Beecher**
