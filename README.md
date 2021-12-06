# Sieve-of-Eratosthenes.py
   a number 'n' is given and you need to print all the prime numbers from 1 to n .so first initialize the list of 'n' numbers by 1 or true assuming that all the no.'s from 1 to n are prime .later start iterating from 2 to n .check if i*i <=n(i.e i starts from 1 to n ) run the while loop until the condition is satisfied. make the l[i]=0 at l[i*i] and l[that no added multiple times till n] so at last print the numbers where l[i]==1 so these are all the prime numbers from 1 to n.
   input :
   10
   output :
   2 3 5 7 
   ex:
   2 3 4 5 6 7 8 9 10
   here l[4,5,6,8,9,10]=0
   so they are not prime rest are prime numbers.
   time complexity of this  algorithm is O(n log log n). 
