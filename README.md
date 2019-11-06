# comp110-worksheet-5

## A)
The algorithm checks the entire list and compares one element of the list to another to look for duplicates, but never the same element. For example it will never check it if i is 5 and j is 5 since they are the same element and therefore checking against for a duplicate doesn't work. It will only return True once two elements of different positions are the same in the list.

## B)
The worst case scenario for this loop would be that it would check through the entire loop, but never actually has a duplicate and therefore returns false. This checks through every possible iteration before ending. Since a regular for loop is linear and can be expressed as O(n) having two do a multidimensional check we are able to multiply them together which is O(n) * O(n) which is just O(n^2) which is quadratic.

## C)
The algoritm is still correct since it checks the entire list against itself using a multidimensional loop. The difference here is that i will iterate up by one each time normally except rather than checking against the max amount of items in the list using j it will just iterate up to j - 1. This means that it checks against a wider range of items a bit more in intervals than before which is more orderly.

## D)
The algoritmn will run twice as fast due to it checking segments of the list against each other in more intervals which increases the chances of it being found much quicker.
