### symbol

It is an atomic entity of length one.
It cannot be broken down into smaller components. {a,b,c,d,e}

|a| = 1
|b| = 1
length is 1. symbol has length 1.

### alphabet
non empty finite set of symbols is called as alphabet. It is denoted by Σ

Σ = {a,b} -> binary alphabet
Σ = {0,1} -> binary alphabet
Σ = {a,b,c} -> ternary alphabet
Σ = {0,1,2,3,........9} -> decimal alphabet

### string
finite sequence of symbols from the alphabet Σ is called as string. it is denoted by w
Σ = {0,1}
w = 0
w =1
w= 00
w =11
w =100
w= 101
w= 0011
w = 1111


No of strings are infinite but the length of each string is finite

### Length of string
if w is any string defined over the alphabet Σ, then no of symbols involved in the string w is called as length of the string, It is denoted by |w|

### empty string
a string of length 0 is called as empty string. It is denoted by ε. w = ε, |w| = 0

1. how many string of length 2 are possible. answer: 4

**how many string of length n are possible if alphabet is also of n types, then the answer is Σ^n**
So it is about if the number of alphabets are 4 and we can make the length upto 5 then total number of combination or number of string will  be: 4^5>>>>

### substring
If u, w be the two string defined over the alphabet Σ, then u is said to be substring of w,if u is obtained from w as it is in the same order.

NOTE:
- If u is a substring of w then |u|<= |w|  
- Every string is a substring to itself and empty string ε is the substring of every string

## types of substring:
```
- trivial substring
let w is any string defined over the alphabet Σ, then the substring w itself and empty string ε is called as trivial substring
```

```
- non trivial substring
let w is any string defined over the alphabet Σ, then any substring of w other than the substring w itself and empty string is called as Non trivial substring
```

