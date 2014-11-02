Prime
=====

Prime class has 5 methods, 

1.  To find nth prime
2.  To check whether a number is prime or not
3.  To get next prime
4.  To get previous prime
5.  To get all prime less than a number


All methods are stateless. Give input and get output. It't just that simple!!

Usage
----------

from prime import Prime
p = Prime()

p.nthprime(500) ## get 500th prime
__Output:__ 3571

p.isprime(23) ## check whether 23 is prime or not
__Output:__ True

p.getnextprime(20) ## Get prime after 20
__Output:__ 23

p.getpreviousprime(20) ## Get prime before 19
__output:__19

p.getallprimes(20) ## Get all primes less than 20
__Output:__[2, 3, 5, 7, 11, 13, 17, 19]
