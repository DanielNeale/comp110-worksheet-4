# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a

| *A* | *B* | *C* |*A* AND *B* AND NOT *C*|
|:---:|:---:|:---:|:---------------------:|
|FALSE|FALSE|FALSE|FALSE                  |
|FALSE|FALSE|TRUE |FALSE                  |
|FALSE|TRUE |FALSE|FALSE                  |
|FALSE|TRUE |TRUE |FALSE                  |
|TRUE |FALSE|FALSE|FALSE                  |
|TRUE |FALSE|TRUE |FALSE                  |
|TRUE |TRUE |FALSE|TRUE                   |
|TRUE |TRUE |TRUE |FALSE                  |

### b

| *A* | *B* | *C* |*A* AND NOT (*B* AND NOT *C*)|
|:---:|:---:|:---:|:---------------------------:|
|FALSE|FALSE|FALSE|FALSE                        |
|FALSE|FALSE|TRUE |FALSE                        |
|FALSE|TRUE |FALSE|FALSE                        |
|FALSE|TRUE |TRUE |FALSE                        |
|TRUE |FALSE|FALSE|TRUE                         |
|TRUE |FALSE|TRUE |TRUE                         |
|TRUE |TRUE |FALSE|FALSE                        |
|TRUE |TRUE |TRUE |TRUE                         |

### c

| *A* | *B* | *C* |(*A* OR NOT *B*) AND (*A* OR *C*)|
|:---:|:---:|:---:|:-------------------------------:|
|FALSE|FALSE|FALSE|FALSE                            |
|FALSE|FALSE|TRUE |TRUE                             |
|FALSE|TRUE |FALSE|FALSE                            |
|FALSE|TRUE |TRUE |FALSE                            |
|TRUE |FALSE|FALSE|TRUE                             |
|TRUE |FALSE|TRUE |TRUE                             |
|TRUE |TRUE |FALSE|TRUE                             |
|TRUE |TRUE |TRUE |TRUE                             |

### d

| *A* | *B* | *C* | *D* |A AND NOT (B OR NOT C) AND (NOT A AND D)|
|:---:|:---:|:---:|:---:|:--------------------------------------:|
|FALSE|FALSE|FALSE|FALSE|FALSE                                   |
|FALSE|FALSE|TRUE |FALSE|FALSE                                   |
|FALSE|TRUE |FALSE|FALSE|FALSE                                   |
|FALSE|TRUE |TRUE |FALSE|FALSE                                   |
|TRUE |FALSE|FALSE|FALSE|FALSE                                   |
|TRUE |FALSE|TRUE |FALSE|FALSE                                   |
|TRUE |TRUE |FALSE|FALSE|FALSE                                   |
|TRUE |TRUE |TRUE |FALSE|FALSE                                   |
|FALSE|FALSE|FALSE|TRUE |FALSE                                   |
|FALSE|FALSE|TRUE |TRUE |FALSE                                   |
|FALSE|TRUE |FALSE|TRUE |FALSE                                   |
|FALSE|TRUE |TRUE |TRUE |FALSE                                   |
|TRUE |FALSE|FALSE|TRUE |FALSE                                   |
|TRUE |FALSE|TRUE |TRUE |FALSE                                   |
|TRUE |TRUE |FALSE|TRUE |FALSE                                   |
|TRUE |TRUE |TRUE |TRUE |FALSE                                   |

## Question 2

### a

![one](https://github.com/DanielNeale/comp110-worksheet-4/blob/master/A%20and%20B%20and%20not%20C.png)

### b

![two](https://github.com/DanielNeale/comp110-worksheet-4/blob/master/A%20and%20not%20(B%20and%20not%20C).png)


### c

![three](https://github.com/DanielNeale/comp110-worksheet-4/blob/master/(A%20or%20not%20B)%20and%20(A%20or%20C).png)

### d

![four](https://github.com/DanielNeale/comp110-worksheet-4/blob/master/A%20AND%20NOT%20(B%20OR%20NOT%20C)%20AND%20(NOT%20A%20AND%20D).png)

## Question 3

### a

| *A* | *B* |NOT (*A* OR *B*)   |NOT *A* AND NOT *B*|
|:---:|:---:|:-----------------:|:-----------------:|
|FALSE|FALSE|TRUE               |TRUE               |
|FALSE|TRUE |FALSE              |FALSE              |
|TRUE |FALSE|FALSE              |FALSE              |
|TRUE |TRUE |FALSE              |FALSE              |

### b

| *A* | *B* |NOT (*A* AND *B*)  |NOT *A* OR NOT *B* |
|:---:|:---:|:-----------------:|:-----------------:|
|FALSE|FALSE|TRUE               |TRUE               |
|FALSE|TRUE |TRUE               |TRUE               |
|TRUE |FALSE|TRUE               |TRUE               |
|TRUE |TRUE |FALSE              |FALSE              |

### c

| *A* | *B* | *C* |(*A* AND *B*) OR (*A* AND *C*) |*A* AND (*B* OR *C*)           |
|:---:|:---:|:---:|:-----------------------------:|:-----------------------------:|
|FALSE|FALSE|FALSE|FALSE                          |FALSE                          |
|FALSE|FALSE|TRUE |FALSE                          |FALSE                          |
|FALSE|TRUE |FALSE|FALSE                          |FALSE                          |
|FALSE|TRUE |TRUE |FALSE                          |FALSE                          |
|TRUE |FALSE|FALSE|FALSE                          |FALSE                          |
|TRUE |FALSE|TRUE |TRUE                           |TRUE                           |
|TRUE |TRUE |FALSE|TRUE                           |TRUE                           |
|TRUE |TRUE |TRUE |TRUE                           |TRUE                           |

### d

| *A* | *B* | *C* |(*A* OR *B*) AND (*A* OR *C*)  |*A* OR (*B* AND *C*)           |
|:---:|:---:|:---:|:-----------------------------:|:-----------------------------:|
|FALSE|FALSE|FALSE|FALSE                          |FALSE                          |
|FALSE|FALSE|TRUE |FALSE                          |FALSE                          |
|FALSE|TRUE |FALSE|FALSE                          |FALSE                          |
|FALSE|TRUE |TRUE |TRUE                           |TRUE                           |
|TRUE |FALSE|FALSE|TRUE                           |TRUE                           |
|TRUE |FALSE|TRUE |TRUE                           |TRUE                           |
|TRUE |TRUE |FALSE|TRUE                           |TRUE                           |
|TRUE |TRUE |TRUE |TRUE                           |TRUE                           |

## Question 4

### a

| *A* | *B* |NOT (*A* AND *B*)  |NOT *A* OR NOT *B* |
|:---:|:---:|:-----------------:|:-----------------:|
|FALSE|FALSE|TRUE               |TRUE               |
|FALSE|TRUE |FALSE              |FALSE              |
|TRUE |FALSE|FALSE              |FALSE              |
|TRUE |TRUE |FALSE              |FALSE              |

### b

| type(*X*) = INT | *X* > 7   |(*X* = int AND *X* > 7) OR ( *X* = float AND *X* > 7)|(*X* = int or *X* = float ) and *X* > 7|
|:---------------:|:---------:|:---------------------------------------------------:|:-------------------------------------:|
|TRUE             |FALSE      |FALSE                                                |FALSE                                  |
|TRUE             |TRUE       |TRUE                                                 |TRUE                                   |
|FALSE            |FALSE      |FALSE                                                |FALSE                                  |
|FASLE            |TRUE       |TRUE                                                 |TRUE                                   |

### c

|*X* = 0|*Y* = 0|*X* = 0 AND *Y* = 0|NOT (NOT *X* OR NOT *Y*)|
|:-----:|:-----:|:-----------------:|:----------------------:|
|FALSE  |FALSE  |FALSE              |FALSE                   |
|FALSE  |TRUE   |FALSE              |FALSE                   |
|TRUE   |FALSE  |FALSE              |FALSE                   |
|TRUE   |TRUE   |TRUE               |TRUE                    |

### d

|*X* > 10|*Y* > 0 |*X* > 10 OR (*X* > 0 AND *Y* > 0)|*X* > 0 AND (*X* > 10 OR *Y* > 0)|
|:------:|:------:|:-------------------------------:|:-------------------------------:|
|FALSE   |FALSE   |FALSE                            |FALSE                            |
|FALSE   |TRUE    |TRUE                             |TRUE                             |
|TRUE    |FALSE   |TRUE                             |TRUE                             |
|TRUE    |TRUE    |TRUE                             |TRUE                             |
