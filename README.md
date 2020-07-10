# BNP Coding Test

 

We’ll implement the code for a checkout system that handles pricing schemes such as “apples cost 50, three apples cost 130.”

 

_**We are looking for a TDD approach and the use of SOLID principles.**_

 

You should provide at a minimum a Scan function and a Total.

 

We’ll be focused on how well you communicate and how you approach the problem.

 

Completing the test, while ideal, is not the most important thing.

 

#### Part 1

 

**This week’s prices:**

 

| Item        | Unit Price      | Special Price  |
| ------------- |:-------------:| -----:        |
| A                        | 50                 | 3 for 130          |
| B                        | 30                 |   2 for 45  |
| C                        | 20                 |                          |
| D                        | 15                 |                          |


Your implementation must allow you to scan items and get a total.

Pseudocode

>One at a time: Scan A, Scan A, Scan C, Scan A, Scan D, Scan B, Scan B, Scan B, Scan A, Scan A

>***Total = 290*** :
>Ax4 (180) + Bx3 (75) + Cx1 (20) + Dx1(15)

 #### Part 2

**Next  week’s prices:**
| Item        | Unit Price      | Special Price  |
| ------------- |:-------------:| -----:        |
| A                        | 60                 | Buy 3 Get 1 D      |
| B                        | 30                 |  Buy 2 Get 1 Free  |
| C                        | 20                 |                          |
| D                        | 15                 |                          |

Pseudocode

>One at a time: Scan A, Scan A, Scan C, Scan A, Scan D, Scan D, Scan B, Scan B, Scan B, Scan A

>***Total=275*** :
>Ax3 (180) + Bx3(60) + Cx1(20) + Dx2(15)
