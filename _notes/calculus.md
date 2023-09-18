
## Theorem. 
### Angle Between Two Vectors

![[Pasted image 20230916083152.png]]

### Proof
$$ \begin{align}
Let $$\boldsymbol w = \boldsymbol u - \boldsymbol v$$ Then applying the law of cosines, \\
$$ \left\vert \boldsymbol w \right\vert^2 = \left\vert \boldsymbol u \right\vert^2 + \left\vert \boldsymbol v \right\vert^2 - 2\left\vert u \right\vert \left\vert v\right\vert cos \theta$$
Since $$ \boldsymbol w = <u_1 - v_1, u_2-v_2, u_3-v_3>, $$
$$\left\vert \boldsymbol u \right\vert^2 = u_1^2 + u_2^2 +u_3^2, \quad 
\left\vert \boldsymbol v\right\vert^2 =  v_1^2 + v_2^2 + v_3^2, \quad \\ 
\left\vert \boldsymbol w \right\vert^2 =   (u_1-v_1)^2 + (u_2-v_2)^2 + (u_3-v_3)^2$$
we can evaluate that
$$2\left\vert u\right\vert \left\vert v\right\vert cos \theta = \left\vert u \right\vert^2 + \left\vert v \right\vert^2 - \left\vert w \right\vert^2 = 2(u_1v_1 + u_2v_2 + u_3v_3)$$
Since $$ 0 \le \theta \le \pi,$$
we have
$$ \theta = cos^{-1}({u_1v_1 + u_2v_2 + u_3v_3 \over \left\vert \boldsymbol u \right\vert \left\vert \boldsymbol v \right\vert })$$
\end{align} $$
