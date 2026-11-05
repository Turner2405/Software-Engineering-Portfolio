# Task 1: Manual Code Walkthrough



Independent Decision points : 14 points

Cyclomatic Complexity : 15 points, This measure exceeds the recommended threshold of 10 by McCabe.



For each destination (local, national, else), the code block (if, else if, else) is duplicated even though there variables may differ the code is duplicated. The variable (wt, dest, p, q) and function name (calcShip) are very unclear and do not give any indication to the meaning of the variable. The code does not provide any input validation at all and there is no error handling inside the function.



### Internal Attributes

* Duplicated Code
* Input Validation
* Error Handling

### Human Judgement

* Unclear Variable Names

# Task 2: Defect Density

System A: 1.5 per KLOC
System B: 2.5 per KLOC

### Cautions on Defect Density
There is no consesus on what constitutes a defect. To make comparisons all partys must count the same way. There is no consensus as to how to measure software size. Defect density is derived from the process of finding defects it may thus tell us more about process that about the product qualtity itself.

### Comparison
System A is under 2 defects per KLOC so would be considered good.

System B is just above the 2 threshold but, it would still be condidered good because its well below the average in the USA and Japan of 5-10 and 4 respective. However, we must consider these averages as not fact as companies are reluctant to publish defect densities.
