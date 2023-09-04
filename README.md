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
![image](https://github.com/sangeethak15-AI/mdp-representation/assets/93992063/aa1f7af6-87d4-4fc6-89b8-ee8948df80d8)


## PYTHON REPRESENTATION:
```
P={
    0:{
        0:[(1.0,0,0.0,False)],
        1:[(1.0,3,0.0,False)],
        2:[(1.0,0,0.0,False)],
        3:[(1.0,1,0.0,False)]
    },
    1:{
        0:[(1.0,1,0.0,False)],
        1:[(1.0,4,0.0,False)],
        2:[(1.0,0,0.0,False)],
        3:[(1.0,2,0.0,False)]
    },
    2:{
        0:[(1.0,2,0.0,False)],
        1:[(1.0,5,0.0,False)],
        2:[(1.0,1,0.0,False)],
        3:[(1.0,2,0.0,False)]
    },
    3:{
        0:[(1.0,0,0.0,False)],
        1:[(1.0,6,0.0,False)],
        2:[(1.0,3,0.0,False)],
        3:[(1.0,4,0.0,False)]
    },
    4:{
        0:[(1.0,1,0.0,False)],
        1:[(1.0,7,1.0,True)],
        2:[(1.0,3,0.0,False)],
        3:[(1.0,5,0.0,False)]
    },
    5:{
        0:[(1.0,2,0.0,False)],
        1:[(1.0,8,0.0,False)],
        2:[(1.0,4,0.0,False)],
        3:[(1.0,5,0.0,False)]
    },
    6:{
        0:[(1.0,3,0.0,False)],
        1:[(1.0,6,0.0,False)],
        2:[(1.0,6,0.0,False)],
        3:[(1.0,7,1.0,True)]
    },
    7:{
        0:[(1.0,4,0.0,False)],
        1:[(1.0,7,1.0,True)],
        2:[(1.0,6,0.0,False)],
        3:[(1.0,8,0.0,False)]
    },
    8:{
        0:[(1.0,5,0.0,False)],
        1:[(1.0,8,0.0,False)],
        2:[(1.0,7,1.0,True)],
        3:[(1.0,8,0.0,False)]
    }
}
```

## OUTPUT:
![image](https://github.com/sangeethak15-AI/mdp-representation/assets/93992063/da660902-c401-4d7b-8406-cc3d4e477651)


## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

*Text Representation

*Graphical Representation

*Python Representation

