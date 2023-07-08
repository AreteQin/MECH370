## How to solve the first-order linear homogeneous differential equation
$$
\begin{aligned}
\frac{dP}{dt}+\frac{P}{\tau}&=0\\
\frac{dP}{dt}&=-\frac{P}{\tau}\\
\frac{1}{P} dP &=-\frac{1}{\tau}dt
\end{aligned}
$$
Apply definite integral on both sides of the equation
$$
\begin{aligned}
\int^t_0 \frac{1}{P} dP &=-\int^t_0 \frac{1}{\tau}dt\\
[ln|P|]^t_0&=-[\frac{1}{\tau}t]^t_0\\
ln|P_t|-ln{P_0}&=-\frac{t}{\tau}\\
ln|P_t|&=ln|P_0|-\frac{t}{\tau}\\
\end{aligned}
$$
Exponentiation on both sides
$$
\begin{aligned}
P_t &= exp(ln|P_0|-\frac{t}{\tau})\\
P_t &= exp(ln|P_0|) \cdot exp(-\frac{t}{\tau})\\
P_t &= P_0 exp(-\frac{t}{\tau})
\end{aligned}
$$