# Clean Code
### 7 Core Clean Code principles to remember

1. #### Names
   1. It must be precise and pass your central idea immediately. That is, it should go straight to the point;
   1. Big names are not a problem. If the situation calls for a long name to demonstrate what it really stands for, this is what should be done.

2. #### Scout Rule
   There is a principle in Scouting that once you leave the area you are camping in, you should leave it cleaner than when you found it.
Bringing the rule into the programming world, the rule means leaving the code cleaner than it was before you messed with it.

3. #### I am the true author of my narrative
   The human being is used to thinking in a narrative way, so the code works that way too. The code is a story, a narrative and, as we programmers are its authors, we need to worry about how it will be told.
   So, to structure a clean code, it is necessary to create simple, understandable and small functions. There are 2 rules for creating the narrative via code:
   1. The functions must be shorts;
   1. They must be even smaller.

4. #### DRY (Don’t Repeat Yourself)
   This principle applies to several areas of development, such as:
   - DB;
   - Tests;
   - Documentation;
   - Codification.
   
   Each piece of knowledge in a system must have a unique representation and be completely unambiguous. In other words, there cannot be two parts of the program that perform the same function.
   
5. #### Comment only what is necessary
   Comments can be made, however, when really necessary. According to Uncle Bob, comments lie, because while codes are constantly being modified, comments don't. They are forgotten and therefore fail to portray the actual functionality of the codes.
   So, if it's to comment, that's just what's necessary and that it be revised along with the code that accompanies it.

6. #### Error Handling
   Knowing how to handle exceptions correctly is a big and important step for an ever-evolving programmer.
   
7. #### Clean Tests
   Testing, in the programming area, is a very important step. A code is only considered clean after it has been validated through tests – which must also be cleaned.
   Some important rules:
   - Fast: The test must be fast, must be allow it to be performed multiple times and all the time;
   - Independent: It must be independent, in order to avoid causing a ripple effect when a failure occurs – which makes it difficult to analyze the problems;
   - Repeatable: It must allow the test to be repeated several times and in different environments;
   - Self-Validation: Well-written tests return with true or false answers, just so the failure is not subjective;
   - Timely: Tests must strictly adhere to punctuality. Also, ideally, they are written before the code itself, as it avoids it becoming too complex to be tested.
       
