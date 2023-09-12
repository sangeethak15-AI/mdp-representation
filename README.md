# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:
 
### Problem Description:
Consider in Tic-tac-toe You have to draw X in one place to win in the game

### State Space:
{0,1,2,3,4,5,6,7,8}

### Sample State:
{0}

### Action Space:
{Up-(0),Down-(1),Left-(2),Right-(3)}

### Sample Action:
{Up-(0)}

### Reward Function:
Win +1(Reward)

loss/draw 0

### Graphical Representation:
![38150e3d-c611-4342-b06a-c3f1f85d76a8](https://github.com/sangeethak15-AI/mdp-representation/assets/93992063/cfb7ef7e-4f79-4a03-b92f-ed6ec3fbcf6b)



## PYTHON REPRESENTATION:
```
P = {
    0 : {
        0 : [(0.91, 0, 0.0, False),(0.09, 1, 0.0, False)],
        1 : [(0.82, 1, 0.0, False),(0.18, 2, 0.0, False)],
        2 : [(0.88, 2, 0.0, False),(0.12, 0, 0.0, False)],
        3 : [(0.75, 0, 0.0, False),(0.25, 0, 0.0, False)]
    },

    1 : {
        0 : [(0.92, 1, 0.0, False),(0.08, 1, 0.0, False)],
        1 : [(0.73, 1, 0.0, False),(0.27, 3, 0.0, False)],
        2 : [(0.88, 3, 0.0, False),(0.12, 0, 0.0, False)],
        3 : [(0.82, 0, 0.0, False),(0.18, 1, 0.0, False)]
    },

    2 : {
        0 : [(0.83,0, 0.0, False),(0.17, 3, 0.0, False)],
        1 : [(0.77, 3, 0.0, False),(0.23, 2, 0.0, False)],
        2 : [(0.91, 2, 0.0, False),(0.09, 2, 0.0, False)],
        3 : [(0.75, 2, 0.0, False),(0.25, 0, 0.0, False)]
    },

    3 : {
        0 : [(0.81, 1, 0.0, False),(0.19, 3, 0.0, False)],
        1 : [(0.88, 3, 0.0, False),(0.12, 4, 0.0, False)],
        2 : [(0.95, 4, 0.0, False),(0.5, 2, 0.0, False)],
        3 : [(0.91, 2, 0.0, False),(0.09, 1, 0.0, False)]
    },

    4 : {
        0 : [(0.85, 3, 0.0, False),(0.15, 5, 0.0, False)],
        1 : [(0.71, 7, 1.0, True),(0.29, 6, 0.0, False)],
        2 : [(0.83, 6, 0.0, False),(0.17, 4, 0.0, False)],
        3 : [(0.81, 4, 0.0, False),(0.19, 3, 0.0, False)]
    },

    5 : {
        0 : [(0.91, 5, 0.0, False),(0.09, 5, 0.0, False)],
        1 : [(0.95, 5, 0.0, False),(0.05, 7, 0.0, False)],
        2 : [(0.95, 5, 0.0, False),(0.05, 7, 0.0, False)],
        3 : [(0.79, 4, 0.0, False),(0.21, 5, 0.0, False)]
    },

    6 : {
        0 : [(0.81, 4, 0.0, False),(0.19, 7, 0.0, False)],
        1 : [(0.86, 6, 0.0, False),(0.14, 4, 0.0, False)],
        2 : [(0.82, 6, 0.0, False),(0.18, 6, 0.0, False)],
        3 : [(0.71, 7, 1.0, True),(0.29, 6, 0.0, False)]
    },

    7 : {
        0 : [(0.83, 7, 1.0, True),(0.17, 7, 0.0, False)],
        1 : [(0.91, 7, 1.0, True),(0.09, 7, 0.0, False)],
        2 : [(0.82, 7, 1.0, True),(0.18, 7, 0.0, False)],
        3 : [(0.95, 7, 1.0, True),(0.05, 7, 0.0, False)]
    }

    8:{
        0 : [(0.81, 4, 0.0, False),(0.19, 7, 0.0, False)],
        1 : [(0.86, 6, 0.0, False),(0.14, 4, 0.0, False)],
        2 : [(0.71, 7, 1.0, True),(0.29, 6, 0.0, False)],
        3 : [(0.86, 6, 0.0, False),(0.14, 4, 0.0, False)]
}
P
```

## OUTPUT:
![image](https://github.com/sangeethak15-AI/mdp-representation/assets/93992063/812a1dbe-0f50-4d73-b787-10e24691cb12)

## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

*Text Representation

*Graphical Representation

*Python Representation

