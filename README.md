# Frank-Wolfe

An application designed to solve a multi-criteria analytical problem by the "ideal point" method using the Frank-Wolf algorithm.

The original task:

![image](https://user-images.githubusercontent.com/22303711/125770779-5cee4513-ca82-4623-99ab-bce970f0799b.png)

In the code, the matrix f is responsible for it.

The original restrictions:

![image](https://user-images.githubusercontent.com/22303711/125771079-77246dbe-5ad2-428a-a08a-cc953c731dc3.png)

In the code, they are located in the matrices A (values to the left of the inequality signs) and b (values to the right of the inequality signs)

Starting point:

![image](https://user-images.githubusercontent.com/22303711/125771313-2fbb1e3b-172b-4734-913a-2d3bd5065066.png),

when n = 22.

In the code, the value of the starting point is specified in the matrix x.
