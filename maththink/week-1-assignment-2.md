# Week 1 - Assignment 2

1. Simplify the following symbolic statements as much as you can, leaving your
   answer in the standard symbolic form. (In case you are not familiar with the
   notation, I’ll answer the first one for you.)

   a. (π > 0) ∧ (π < 10)  : 0 < π < 10
   b. (p ≥ 7) ∧ (p < 12)   : 7 <= p < 12
   c. (x > 5) ∧ (x < 7)     : 5 < x < 7
   d. (x < 4) ∧ (x < 6)     : x < 4
   e. (y < 4) ∧ (y² < 9)   : x < 3
   f. (x ≥ 0) ∧ (x ≤ 0)     : x = 0

2. Express each of your simplified statements from question 1 in natural
   English.

   a. zero is smaller than pi and pi is smaller than ten
   b. seven is smaller than or equal to p and p is smaller than twelve
   c. five is smaller than x and x is smaller than seven
   d. x is smaller than four
   e. x is smaller than three
   f. x equals zero.

3. What strategy would you adopt to show that the conjunction 
   φ1 ∧ φ2 ∧ . . . ∧ φn is true?

   Starting from φ1 I would verify that it is true, 
   continuing with the next φx
    if φx is false ⇒ conjunction is false
    if φx = φn and φx is true ⇒ conjunction is true

4. What strategy would you adopt to show that the conjunction 
   φ1 ∧ φ2 ∧ . . . ∧ φn is false?

   Same is in 3.

5. Simplify the following symbolic statements as much as you can, leaving your
   answer in a standard symbolic form (assuming you are familiar with the
   notation):

   a. (π > 3) ∨ (π > 10) : π > 10

      Incorrect, the correct answer is π > 3. Reasoning: the disjunction starts
      to be true as soon as π is greater than 3. This is definitely the case
      when π is greater than 10 so the first disjunct is more informative.

   b. (x < 0) ∨ (x > 0)  : x ≠ 0
   c. (x = 0) ∨ (x > 0)  : x ≥ 0
   d. (x > 0) ∨ (x ≥ 0)  : x ≥ 0
   e. (x > 3) ∨ (x² > 9) : x > 3 [Incorrect]

      x² > 9 means: (x > 3) ∨ (x < -3). The first disjunct is also the first
      disjunct of the original problem, making it superfluous. Consequently,
      the statement should be simplified to: x² > 9.

6. Express each of your simplified statements from question 5 in natural
   English.

   a. Pi is greater than 10
   b. x is unequal to zero
   c. x is greater than or equal to zero
   d. x is greater than or equal to zero
   e. x is greater than three

7. What strategy would you adopt to show that the disjunction
   φ1 ∨ φ2 ∨ . . . ∨ φn is true?

   let x = 1
   let disjunction = false
   while x ≤ n do
     if φx = true then
        disjunction = true
        break
     x = x + 1

    In plain language: Show that at least one of φ1, ..., φn is true.

8. What strategy would you adopt to show that the disjunction 
   φ1 ∨ φ2 ∨ . . . ∨ φn is false?

   Show that all φ1, ..., φn are false.

9. Simplify the following symbolic statements as much as you can, leaving your
   answer in a standard symbolic form (assuming you are familiar with the
   notation):

   a. ¬(π > 3.2) : π < 3.2 [Incorrect: π ≤ 3.2]
   b. ¬(x < 0)   : x ≥ 0
   c. ¬(x² > 0)  : x = 0
   d. ¬(x = 1)   : x ≠ 1
   e. ¬¬ψ        : ψ

10. Express each of your simplified statements from question 9 in natural
    English.

    a. π is smaller than 3.2
    b. x is greater than or equal to zero
    c. x equals zero
    d. x is not equal to one
    e. psi

11. Let D be the statement “The dollar is strong”, Y the statement “The Yuan is
    strong” and T the statement “New US–China trade agreement signed”. Express
    the main content of each of the following (fictitious) newspaper headlines
    in logical notation. (Note that logical notation captures truth, but not
    the many nuances and inferences of natural language.) How would you justify
    and defend your answers?

    a. Dollar and Yuan both strong : D ∧ Y
       
       The word both refers to Dollar and Yuan.

    b. Yuan weak despite new trade agreement, but Dollar remains strong
       
       ¬Y ∧ T ∧ D

    c. Dollar and Yuan can’t both be strong at same time.

       (D ∧ ¬Y) ∨ (¬D ∧ Y)

       Answer from KD (which is simpler): ¬(D ∧ Y)
    
    d. New trade agreement does not prevent fall in Dollar and Yuan

       T !⇒ (¬D ∧ ¬Y) [Incorrect]

       The answer from KD: T ∧ ¬D ∧ ¬Y

    e. US–China trade agreement fails but both currencies remain strong

      ¬T ∧ D ∧ Y



