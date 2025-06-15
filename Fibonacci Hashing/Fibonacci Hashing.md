### Fibonacci sequence
$$
\begin{cases}
	F(0) = 0 \\
	F(1) = 1 \\
	F(N) = F(N - 1) + F(N -2) \\
\end{cases}
$$
### Golden angle
Assume that I want to make a program that when a user clicks on the screen, a leaf will be added around a center.
- **Case 1**: I know exactly how many clicks that user would make. I can assume that I have a circle. Now, let say that number of clicks is $n$, I can easily divide my circle in to $n$ parts with the angle separates 2 success parts is $\frac{360\degree}{n}$. With this division strategy, after $n$ steps, I can go back to the beginning.
- **Case 2**: I do not know the number of clicks would be made. If I am not careful, I can make those leafs overlap. Luckily, I have a tool, a *golden angle* that will never overlap. When user clicks, I will add another leaf that is separate from the last leaf an angle $\alpha$ ($\alpha$ is the *golden angle*).
$$
	\phi \approx1.61803398875
$$
$$
	\alpha =360 - \frac{360\degree}{\phi}\approx 137.5\degree
$$
Now I can do easily add more leafs into my circle without worrying about overlapping.
![[golden-ratio-animation.gif]]
## Fibonacci hashing
![[Pasted image 20250608201731.png]]
Normally, we let a = 2654435759. Why?
We can get a from this
$$
a \approx 2^{32} \times (1 -\phi)
$$
Or we can claim that $a \approx (2^{32} \times \phi) \text{ truncated to 32 bits number}$.
**WHY?**
We got 
$$
	\begin{cases}
		2^{32} \times \phi \approx 6949403065_{10} \\
		6949403065_{10} = 110011110001101110111100110101110_{2} \\
	\end{cases}
$$
$$
	\Rightarrow 6949403065_{10} \text { truncated to 32 bits is } 10011110001101110111100110101110_{2} = 2654435758_{10}
$$