# dismathportfolio-arracarandang
dismathportfolio-arracarandang created by Classroom for GitHub

#Week1

DisMath or Discrete Mathematics, is a subject where the only thing you have to deal with is logic.And from the comments of the higher batch or those who already took up Dismath, it is really a hard subject to pass. 

Sir Cabatuan, our professor in dismath, is an ECE professor who has traveled a lot of countries where he 

I've learned the following in our first day:

a.  Proposition- w/c is a declarative sentence; either True or False

b.  Examples on how to distinguish if the statement is a proposition or not

c.  Truth Values: T/1 (true proposition),  F/0 (false proposition) 

d.  Logical operators such as: 

  1. Conjunction (^) 
  
  -"p and q"
  
  -TRUE when both p and q are T
  
  -minimum of p and q
  
  2.Disjunction (∨) 

  -"p or q"
  
  -FALSE when both are false
  
  -maximum of p and q
  
  3.Exclusive Disjunction (⊕)
  
  -"p or q" (but not both)
  
  -TRUE if exactly one of p and q is True
  
  4.Implication (→) 
  
  - "if p, then q", etc.
  
  -TRUE when pa and q are True

  -TRUE when p is false
  
  5.Biconditional (↔) 
  
- "if and only if"
  
  -TRUE when both p and q are both True and False

  6. Negation (-) - "not p"
  
e. Truth table- it is a list of all posiible inputs/ combination of inputs w/ corresponding outputs

f. (2^n) - the formula to get the number of rows; n as the number of variables


#Week2

I've learned the following:

a. Contrapositive

  - "-q → -p"
  
  - same truth value with p→q
  
b. Inverse

  - "-p→-q"
  
c. Converse

  - "q→p"
  - 
d. Precedence of logical Operators

   (¬) - 1
   
   (^) - 2
   
   (v) - 3
   
   (→) - 4
   
   (↔) - 5
   
e. System Specifications

  - should be CONSISTENT( not conflicting requirement that could be used to contradict)

f. Propositional Equivalences

  1. Tautology (always True)

  2. Contradiction (always False)
  
  3. Contingency (neither True nor False)
  
g. Logical equivalences

  - compound proposition have same truth values in all possible cases
  
  - "p = q"
  
  - different laws:
  
  Identity Law

  Domination Law
  
  Idempotent Law
  
  Double Negation
  
  Commutative Law
  
  Associative Law
  
  Distributive Law
  
  De Morgan's Law
  
  Absorption Law
  
  Negation Law

h. Propositional Logic

  - deals w/ proposition as whole

i. Predicate Logic

  - has internal structure in terms of SUBJECT and PREDICATE

j. Quantifiers

  - indicates generality of subject/ predicate

  - kinds:

      Existential quantifier - is true if and only if P(x) is true for atleast 1 value of x in the domain

      Universal quantifier - asserts that a property is true for all values of a variable in a particular domain

  
  
  #Week3

On week 3 we were able to tackle the RULES OF INFERENCE:

Rules of Inference

-validity of conclusion, if and only if premises are all true
  
  Argument
    - a sequence of statements that end with a conclusion
    
  Validity of the Argument
    
    -means that the conclusion, or the final statement is dependent on the structure of the premise
    
  Argument Form
  
  -propositional logic is a sequence of compound propositions involving propositional variables
  
  Validity of Argument Form
  
  -means that whatever the substituted propositions are for the propositional variables in the premise, still the conclusion is true  if the premises are all true
    
  Fallacies
  
  -incorrect reasoning that leads to invalid arguments
  

METHODS OF PROOF

  Theorems
  
    - a statement that can be shown to be true; also referred to as facts or results
    
  Proof
  
    -a valid argument that establishes the truth of the theorem
    
1. Direct Proofs (in Conditional Statements)

  1.a Assume that P is true
  
  1.b Show that Q is also true based on statement 1
  
  * Odd Numbers {2k + 1 | k is an integer}
  
  * Even Numbers {2k | k is an integer}
  
    example: 0 is an even number

#Week4

2. Proof by Contraposition (Indirect proofs)

  *If p is complicated than q, use proof by contraposition

    2.a Assume -q is true
  
    2.b Show that -p is also true based on statement 1
    
3. Vacuos Proof (-p → (p→q))

    3.a show that p is false, because p→q must be true when p is false
  
4. Trivial Proof (q → (p→q))

    4.a show that q is true, it follows that p→q must also be true
  
5. Proof by Contradiction

    5.a Assume that the premise is not true 
  
    { ¬(premise) = T }  - negation of the whole premise
  
    5.b Show that statement 1 will end up in a contradiction 
  
*Rational Numbers 

    {a/b | a,b are integers, b not equal to 0, a & b doesn't have a common factore except +- 1}
    
    {in lowest terms}
    
Proofs of Equivalence ( Biconditionals)

    p ↔ q , p→q and q→p are both true 

    *q→p is a converse
    

#Week5 

There's a continuation of the discussion about the proof by equivalence with some examples to exercise us with. 

One example is: "Every positive integer is the sum of the squares of 2 integers." This is proven by counterexample  for it can't be expressed as the sum of the squares of 2 integers. 

Mathematical Induction is also discussed in which it is a proof technique used to prove results about wide range of objects. 

1. Basis: Show P(1) or P(0) to be true.

2. Inductive step

2.a. Assume P(k) is True. 

2.b. Show P(k+1) is True. 

#Week6

SUMMATION - notation for sum of am, am+1, ..., an is ∑ai=m ai where i is the index of summation.
        Σ “sigma”
    
    
    RECURSIVE/INDUCTIVE DEFINITION
        
        1. Basis step: specify the value at zero
       
        2. Recursive step: Find a rule for finding its value at an integer number from the values at smaller integers.
        example: f(0) = 3, f(n+1) = 2f(n) + 3

    
RECURSIVE ALGORITHM - solves a problem by reducing it to an instance with smaller input

    
PROGRAM CORRECTNES - to ensure that a program gives the correct output
        
        
PROGRAM VERIFICATION - A program is said to be correct if it produces the correct output for every possible input.
           
            1. Show that the correct answer is obtained if the program terminates.(Partial correctness)
           
            2. Show that the program always terminates
        
        
PARTIAL CORRECTNESS
           
            initial assertioN (p)- gives the properties that the input values must have.
           
            final assertion (q) - gives the properties that the output of the program should have, if the program did what was intended.

    
HOARE TRIPLE p{S}q
       
        S is said to be partially correct with respect to the initial assertion p and the final assertion q if whenever p is true for the input values of S and S terminates, then q is true for the output values of S

    
    RULES OF INFERENCE - a program is correct by splitting the program into a series of sub-program and show each sub-program is correct.
    
    p{S1}q
    q{S2}r
  ______________
  ∴ p{S1;S2)r 

    * CONDITIONAL STATEMENTS
        (p ∧ condition) {S} q
        (p ∧ ¬condition) → q
        __________________________________________
        ∴ p {if condition then S} q
        
        
        IF-ELSE STATEMENT
        (p ∧ condition) {S1} q
        (p ∧ ¬condition) {S2} q
        _____________________________________
        ∴ p {if condition then S1 else S2} q

    POWER SERIES
    
#WEEK7

Intoduction to Set Theory

In this week discussion, 'sets' is introduced, in which sets are collection of objects used extensively in counting (unordered collection)

An example given is to distinguish whether 1 and {1} is equal or not. And the answer is 1 is not equal to {1}, for '1' is a number and '{1}' is a set containing number 1.  

-An empty set is a set with no elements, { }. 

-Set {1,2,5} = Set {5,3,1} = Set {1,3,3,5,5,5} *It is equal if and only if the given sets have the same elements

#WEEK8

It is also discussed about Cardinality of a set, it is the number of elements it contains. Example: 

    |S|=26 (S as the set of english alphabet)

    |N| is a set of natural numbers. |N|='aleph-nought'/infinite numbers

Power Set is also discussed as the set of all subsets of the set S, 'P(S)'. To get the number of subsets needed in a power set, formula :(2^n) can be used. Example: 

    2^n= 2^3= 8 subsets for set {0,1,2}
    
    Power set of {0,1,2}: { {}, {0}, {1}, {2}, {0,1}, {1,2}, {0,2}, {0,1,2} }
    
We also discussed the different set operations like Union, Intersection ad disjoint. The difference between these three is that Union is a set that contains those elements that either at the first set or at the second set or both. While for intersection, it is a set that contains the elements present in both given sets. and for the disjoint, it is if the intersection is the empty set. 

Some of the Set Identities is also discussed like Identity Laws, De Morgan's and Complementation law/Double Negation Law.

#WEEK9

'Let A & B be sets. A function f from A to B is an assignment of exactly one element of B to each element of A.'

Functions are called mappings/ transformations. It has the domain and co-domain. Domain is the set of "input" or argument values for which the function is defined. While co-domain or target set of a function is the set Y into which all of the output of the function is constrained to fall. Co-domain is sometimes equal with the range. Range is the actually occuring values. 

Different types of functions are discussed such as One-to-One (Injective), Onto-function (Subjective), One-to-one correspondence(Bijection).

    One-to-one function (Injective)
      -no value is used by more than one value in the domain. 
      
    Onto Function (Subjective)
      -functions have equal range and co-domain
      -for all values in the co-domain, there is a value in the range mapped to it. 
     
     One-to-one correspondence(Bijection)
      
#WEEK10

Algorithm - is a finite set of precise instructions for performing a computation or for solving a problem. In writing an algorithm preconditions and post-conditions are needed. Pre-conditions are statements that describe a valid input. 

Pseudocodes are also used to describe an algorithm. For which it means that it provides an intermediate step between an English language description of an algorithm and an implementation of this algorithm in a programming language. 

    Algorithm 1: Finding the max element of the sequence
    
      Input: Find Max ( {a1 , a2 , a3,..., an: it is an element of an integer})
      
      Output: Max element
      
        max=a1
        
        for i= 2 to n
        
        {if max < ai, then max = ai }
        
  ______________________________________________________________
  
  Algorithm 2: Linear Search/ Sequential Search
  
  Input: Search ( {a1, a2, a3,...,an: it is an element of an integer} x as the searched element)
  
  Output: location of x = i
  
    loc = i if found, loc = -1 if not found
  
  i=1
  
  while ((x != ai) ^ (i <= n))
  
   {i=i+1};
  
  if (i<=n)
  
    {loc = 1};
    
  else
  
    {loc=-1};
    
  ______________________________________________________________
  
  Algorithm 3: Binary Search
  
  Input: Search ( {a1, a2, a3,...,an: it is an element of an integer} x as the searched element)
  
  Output: location, loc
  
      i=begin=1
      
      j=end=n
      
      mid=[(i+j)/2]
      
      if (x>am) then i=m+1; else (j=m);
      
      if x = ai then location = i
      
      else location = 0
      
 ______________________________________________________________
 
 Algorithm 4: Bubble Sort
 
 Input: bubble sort(a1, a2, a3,..., an| n >= 2)
 
 Output: {X1<X2<X3<...<Xn}
 
 for i = 1 to n-1
 
    for j =1 to n-i
    
      if (aj>aj+1) then interchange (aj and aj + 1)
      
      
______________________________________________________________

Algorithm 5: Insertion Sort

Input: insertion sort(a1, a2, a3,..., an)
 
Output: {X1<X2<X3<...<Xn}
 
  for j = 2 to n
  
    { i=1
    
        while aj>ai
        
          i = i+1
        
      m=aj
      
      for k=0 to j-i-1
      
        aj-k= aj-k-1
        
      ai=m 
      
    }
    
 ______________________________________________________________
 
 Algorithm 6: Greedy Algorithm
 
 
 #WEEK10
 
 Growth of Functions 
 
  Big-O notation- is the estimated number of operations an algorithm uses as its input grows
  
                - does not provide a lower bound for the size of f(x)
  
      f(x) <= C (g(x)) whenever x > k
    
      To prove that a function is a Big-O of another function, provide witnesses such as C and k. And to get C, use the point
      of intersection of the two functions. *If k is a negative, start at 0 (k=0 is valid)
  
  Big-Omega - for the lower bound (Big-Ω)
  
  Big-Theta - for both upper and lower bound (Big-θ)  
  
    
  
      


    







  
  
  
  
  


  
  
    
  


    
 
  
  
  
  
               
