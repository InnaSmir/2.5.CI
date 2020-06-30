# JaCoCo Coverage Counters #

## **Instructions:**

Instruction coverage provides information about the amount of code that has been executed or missed. This metric is completely independent from source formatting and always available, even in absence of debug information in the class files.

## **Branches:**

JaCoCo also calculates branch coverage for all if and switch statements. This metric counts the total number of such branches in a method and determines the number of executed or missed branches.
*No coverage: No branches in the line has been executed (red diamond)
*Partial coverage: Only a part of the branches in the line have been executed (yellow diamond)
*Full coverage: All branches in the line have been executed (green diamond)

## **Cyclomatic Complexity:**

JaCoCo also calculates cyclomatic complexity for each non-abstract method and summarizes complexity for classes, packages and groups. Cyclomatic complexity is the minimum number of paths that can, in (linear) combination, generate all possible paths through a method. Thus the complexity value can serve as an indication for the number of unit test cases to fully cover a certain piece of software. Complexity figures can always be calculated, even in absence of debug information in the class files.

## **Lines:**

For all class files that have been compiled with debug information, coverage information for individual lines can be calculated. A source line is considered executed when at least one instruction that is assigned to this line has been executed.
*No coverage: No instruction in the line has been executed (red background)
*Partial coverage: Only a part of the instruction in the line have been executed (yellow background)
*Full coverage: All instructions in the line have been executed (green background)
