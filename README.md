# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.
   1. Text representation
   2. Graphical representation
   3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
Problem Description
To develop an environment consisting of a mobile tower as the start and the house as the goal. The aim is to make sure the network signals reaches the house.

### State Space
{0,1,2,3,4,5,6,7}

### Sample State
4

### Action Space:
* {0) Moving Up
* {1} Moving Right
* {2} Moving Down
* {3} Moving Left

### Sample Action
{1} Moving Right

### Reward Function

* +1 - If the goal is reached
* 0 - Otherwise

### Graphical Representation

![reinfo exp1 img](https://github.com/Lakshmipriya-P-AI/mdp-representation/assets/93427923/28f63886-7129-42dd-9e6f-3e6f4a16b1b4)


## PYTHON REPRESENTATION:
```
P = {
    0 : {
        0 : [(0.91, 0, 0.0, False),(0.09, 1, 0.0, False)],
        1 : [(0.82, 1, 0.0, False),(0.18, 2, 0.0, False)],
        2 : [(0.88, 2, 0.0, False),(0.12, 0, 0.0, False)],
        3 : [(0.75, 0, 0.0, False),(0.25, 0, 0.0, False)],
    },

    1 : {
        0 : [(0.92, 1, 0.0, False),(0.08, 1, 0.0, False)],
        1 : [(0.73, 1, 0.0, False),(0.27, 3, 0.0, False)],
        2 : [(0.88, 3, 0.0, False),(0.12, 0, 0.0, False)],
        3 : [(0.82, 0, 0.0, False),(0.18, 1, 0.0, False)],
    },

    2 : {
        0 : [(0.83,0, 0.0, False),(0.17, 3, 0.0, False)],
        1 : [(0.77, 3, 0.0, False),(0.23, 2, 0.0, False)],
        2 : [(0.91, 2, 0.0, False),(0.09, 2, 0.0, False)],
        3 : [(0.75, 2, 0.0, False),(0.25, 0, 0.0, False)],
    },

    3 : {
        0 : [(0.81, 1, 0.0, False),(0.19, 3, 0.0, False)],
        1 : [(0.88, 3, 0.0, False),(0.12, 4, 0.0, False)],
        2 : [(0.95, 4, 0.0, False),(0.5, 2, 0.0, False)],
        3 : [(0.91, 2, 0.0, False),(0.09, 1, 0.0, False)],
    },

    4 : {
        0 : [(0.85, 3, 0.0, False),(0.15, 5, 0.0, False)],
        1 : [(0.79, 5, 0.0, False),(0.21, 6, 0.0, False)],
        2 : [(0.83, 6, 0.0, False),(0.17, 4, 0.0, False)],
        3 : [(0.81, 4, 0.0, False),(0.19, 3, 0.0, False)],
    },

    5 : {
        0 : [(0.91, 5, 0.0, False),(0.09, 5, 0.0, False)],
        1 : [(0.95, 5, 0.0, False),(0.05, 7, 0.0, False)],
        2 : [(0.77, 7, 1.0, True),(0.23, 4, 0.0, False)],
        3 : [(0.79, 4, 0.0, False),(0.21, 5, 0.0, False)],
    },

    6 : {
        0 : [(0.81, 4, 0.0, False),(0.19, 7, 0.0, False)],
        1 : [(0.71, 7, 1.0, True),(0.29, 6, 0.0, False)],
        2 : [(0.82, 6, 0.0, False),(0.18, 6, 0.0, False)],
        3 : [(0.86, 6, 0.0, False),(0.14, 4, 0.0, False)],
    },

    7 : {
        0 : [(0.83, 7, 1.0, True),(0.17, 7, 0.0, False)],
        1 : [(0.91, 7, 1.0, True),(0.09, 7, 0.0, False)],
        2 : [(0.82, 7, 1.0, True),(0.18, 7, 0.0, False)],
        3 : [(0.95, 7, 1.0, True),(0.05, 7, 0.0, False)],
    }
}
```

## OUTPUT:

![265270435-20ef6215-f394-4aa0-9c3a-ac15494e6d09](https://github.com/Lakshmipriya-P-AI/mdp-representation/assets/93427923/1e28f004-7146-4462-ab79-a5d99414631c)

## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

  1. Text Representation
  2. Graphical Representation
  3. Python Representation

