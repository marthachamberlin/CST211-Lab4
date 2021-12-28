# CST211-Lab4
Lab 4
Stack – List Implementation
Description
Develop a Stack class that is based upon a List (from Lab 2).
UML Class Diagram

typename: T

Stack

private:
* m_stack: List
* num_elements: int

public:
* Push(in data:T): void
* Pop(): T
* <<const>> Peek(): T
* <<const>> getNumElements(): int
* <<const>> isEmpty(): bool

Stipulations
Throw Underflow and Overflow exceptions using your Exception class where appropriate.
Although not shown in the UML class diagram, include the appropriate manager functions. (Be sure to have the correct ones! ☺)
Selected function explanations:
Push – Puts a data item on the top of the stack.
Pop – Removes and returns the top of the stack.
getNumElements – How many items are currently on the stack.

Deliverables
One file including:
Your code
Your test(s) similar to Lab1_test.cpp & Lab2_test.cpp and their results

