# COVID-19
Python program for calculating the Covid-19 doubling period using data from outside of China

## Math
### Model
$$y=A2^{t/\tau}$$
$\tau$ is the doubling period.
### Linearizing
$$\ln{y}=\ln{A}+\frac{t,\tau}\ln{2}$$
### System of equations from measurements
$$\ln{y_{1}}=\ln{A}+\frac{t_1}{\tau}\ln{2}$$
.
.
.
$$\ln{y_{n}}=\ln{A}+\frac{t_n}{\tau}\ln{2}$$
### Matrix Representation
$$\begin{pmatrix}y_1 \\ \vdots \\ y_n \end{pmatrix}=\begin{bmatrix}t\ln{2} & 1 \\ \vdots & \vdots \end{bmatrix}\begin{bmatrix}\frac{1}{\tau} \\ \ln{A} \end{bmatrix}$$

