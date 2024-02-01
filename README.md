# Tree-Creation-and-Traversal
Tree Creation and Traversal
Task: Tree Creation and Traversal
1. Given an Nary-Tree input serialisation which represents the level order
traversal of a tree. Each group of children is separated by the None value (See
examples). The task is to create a tree from this input and return the root node
of the same.
2. Given the root of an n-ary tree, print the postorder traversal of its nodes'
values.
You can use the following definition of the Node for tree creation:

from typing import List
from future import __annotation__
class Node:
def __init__(self, val: int, children: List[Node] = None):
self.val = val
self.children = children
class Solution:
def createTree(input: List[int]) -> Node:
pass
def traverseTree(root: Node) -> None:
pass

Input Example I
input: [1, None, 3, 2, 4, None, 5, 6]

Tree outlook:
Traversal Output: [5, 6, 3, 2, 4, 1]

Input Example II
input: [1, None, 2, 3, 4, 5, None, None, 6, 7, None, 8, None, 9, 10, None, None, 11,
None, 12, None, 13, None, None, 14]

Tree outlook:
Traversal Output: [2, 6, 14, 11, 7, 3, 12, 8, 4, 13, 9, 10, 5, 1]
Instructions:
Setup:
● Only Python installation is needed, no external library is required.
Additionally, you can install any library whichever is required.
Implementation:
● All extreme test cases should be handled.
● The script should be able to accept an array of comma separated
integers in the argument.
● Output should be the tree traversal of the provided input.
● There are no restrictions on what library you want to use.
Testing:
● Test your code against given samples and match the output of the
traversal.
Submission:
● Push your code on a version control platform like GitHub or GitLab.
● Include clear instructions on how to run the project locally. Also add
installation steps for an external library, if used any.
● Provide a README with any additional information or notes.
