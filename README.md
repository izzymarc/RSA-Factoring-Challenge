#### 0\. Comprehensive Number Factorization#advanced

Engage in the task of factorizing as many integers as possible into two smaller integers.

-   How to use: `factors <file>`
    -   `<file>` refers to a file that contains natural numbers for factorization.
    -   Each line should contain a single number.
    -   All numbers are guaranteed to be valid natural numbers above 1.
    -   There will be no empty lines, nor spaces before or after the numbers.
    -   Each file concludes with a new line.
-   Format of output: `n=p*q`
    -   Each line should display one set of factors.
    -   `p` and `q` need not be prime.
    -   Refer to the provided example.
-   You may choose the order in which to process file numbers.
-   Your program should be self-sufficient without needing any external installations.
-   Time constraint: Programs exceeding 5 seconds of runtime will be terminated.
-   Submit all your scripts and source code in your repository.
    -   Only the `factors` executable will be run.

#### 1\. RSA Number Decomposition Challenge#advanced

RSA Laboratories outlines that each RSA number `n` has corresponding prime numbers `p` and `q`, where `n = p × q`. The challenge lies in deducing `p` and `q` from `n`.

This task is an extension of task 0, with the following variations:

-   Both `p` and `q` are always primes.
-   Each file contains just a single number.

What's the largest number you can decompose in under 5 seconds?

-   For further reading: [RSA Factoring Challenge](https://intranet.hbtn.io/rltoken/8F5ClnjOFgDcNZXxeyrHxg "RSA Factoring Challenge")