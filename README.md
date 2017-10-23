# hello-world
This is my first *repository*
, i'm a student trying to learn to code in order to become an **MVP**

I started to use GitHub in order to complete some assignments from my classes in [IES Francesc de Borja Moll](http://www.iesfbmoll.org/)

For my assignment in LLMM i had to have a repositry with all this things:
  - Title
  - Lists
  - Links
  - Something written in bold and something written in italic
  - Code and Syntax Highlighting
  - Tables

And in this table i can show with which programing languages i have experience:

Languages | Experience
------------ | -------------
Java | Subjects in the UIB
Python | Some weeks in IES FBM
  
  
Now i will present some code written in class, which can tell you if a matrix is antisymmetric:
  
```python

def esAntisimetrica(matriz):
    i = 0
    j = 0
    while i <= len(matriz) - 1:
        while j <= len(matriz[i]) - 1:
            if matriz[i][j] != - matriz[j][i]:
                return 'False'
            j = j + 1
        i = i + 1
    return 'True'

#And here are some test cases

print(esAntisimetrica([[0, 1, 2],[-1, 0, 3],[-2, -3, 0]]))

print(esAntisimetrica([[0, 1, 2],[-1, 0, -2],[2, 2, 3]]))

```
