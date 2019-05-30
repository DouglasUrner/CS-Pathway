# Reading In CS

## Reading Skills For CS

* **Disecting Project Specs**  
To understand what is required of you.
* **Reading Documentation**  
To understand how the tools you are using work.
  - "Formal" API and tool documentation
  - Tutorials
* **Reading Code**  
To understand what the code does, how it works, and to find and fix bugs.
* **Reading Output**
  - Editor/IDE messages
  - Compile time errors and warnings
  - Runtime errors and warning (exceptions)
  - "Intentional" output - "normal" program output (understanding how it is constructed)
* **Communicating to Collaborate**  
  - Peers
  - Management
  - Clients
  - Users
  - Reviewers
  
   Recognizing that roles can overlap.
  
Notes towards a [Reading Assessment & Intervention Protocol](https://docs.google.com/document/d/1_uaE2YR7COytJC3DQLxi6bECeaFk97nYWnssua0OvdQ/edit?usp=sharing).

## Assessing Reading Skill & Diagnosing Problems

* Assess specific skills in isolation - e.g., avoid making a writing task a reading assessment, or at the very least do not make writing quality a part of reading assessment.
  - Multiple choice.
* Allow alternative demonstrations of reading proficency - oral, drawing, write or debug code.

## Reading Interventions

* Building vocabulary
* Taking notes
* Modeling "reading behaviors"

### For Reading Code

Tranferable skills and skills that are, more or less, specific to reading code.

* Observation skills - noticing differences between code segments
* "Parts of speech"
* Teach code structure (blocking, matching braces, scope, how the language or runtime system works)
* Teach syntax
  - Recognizing syntax errors
  - Predicting the result of errors
  - Recognizing syntactic errors that lead to unexpected/incorrect execution of the code. For example in a C-like language, this code snippet probably does not do what the author intended - although the syntax is accepted by the parser.
    ```c
    if (a == b);  // Empty if block
      c++;        // Always executed
    ```
* Variable declarations vs. usage
* Function definition vs. function calls
* Convention vs. requirement - e.g., in JavaScript variable names are **camelCased** by convention, but are not allowed to begin with a digit.
* Patterns (counter pattern, array iteration)
  - Recognizing code that does something you want and using it as a template.
  - _Gang of Four_ - reusable solutions.

Reading error messages and strategies for resolving them.

## Demonstrating Mastery
