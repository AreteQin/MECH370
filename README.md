# MECH370
Useful information for Concordia Course MECH370

## Lab report
[Example file](./report_example.pdf) 

## Lab 1

[Lab1 Slides](./lab1_slides.pdf)

### If you encounter the following error:
![](images/delete_the_shadowing_file.png)

It is because the file name of script file is the same as the name of the model file. Changing the name of the script file to something different can solve the problem.

### Why does $\frac{1}{s}$ represent the integrator? According to the Laplace transform of integral:

$$
\mathscr{L}[\int g(t) d t]=\int_0^{+\infty}\int g(t)dt e^{-st}dt = 
\frac{G(s)+[\int g(t) d t]_{t=0}}{s}
$$

where $G(s) = \mathscr{L}[g(t)]$

### Simulink model with block labels
![](Lab1_simulink.png)

### Simscape model with block labels
![](Lab1_simscape.png)
