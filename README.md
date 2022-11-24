# Finite-Automaton-Lab3

Statement: Write a program that reads the elements of a finite automaton from a file and:

    Display set of states, alphabet, transitions, set of final states
    Documentation should also include in BNF or EBNF format the form in which the FA.in file should be written
### Solution    
  
transition := "(" statement, alphabet ")" "->" statement 

statement := initialStatement | normalStatement | finalStatement
initialStatement := "{" "q" digit "}"

digit := "0" | "1" | ... | "9"

letter := "a" | "b" | ... | "z" | "A" | "B" | ... | "Z"

normalStatement := "(" "q" digit ")"

finalStatement := "[" "q" digit "]"

alphabet := digit | letter


### Pentru exemplu am folosit ex 1 semiar 4

[Project](Automaton.png)
    
