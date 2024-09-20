# MATH3310_Discrete_HW2

1. item Recall that we discussed number systems by writing an ordered triple $(X, Y, Z)$, where $X$ is a set of things we call \`numbers',
$Y$ is the notation for an operation we call \`addition', and $Z$ is notation for what we call `multiplication'.
We can do something analogous with \emph{Logical Systems}: we specify the set of statements, the function that determines truth, and the
logical operations and operators.  For the logical system that we (and essentially everyone) use, lets use the notation
$(\mathcal{M}, \Phi, \implies, \wedge, \vee, \neg)$ to mean that $\mathcal{M}$ is the set of statements we work with,
$\Phi$ is the function that assesses truth, and the others are the logical operations and operator.
Please prove or disprove that the our logical system $(\mathcal{M}, \Phi, \implies, \wedge, \vee, \neg)$ can be replaced with
		$(\mathcal{M}, \Phi, \nabla)$, where $\nabla$ is defined as follows.  For $x, y \in \mathcal{M}$, $x \; \nabla\;y$ is equivalent to
		$\neg(x \vee y)$.

2. \item Prove that the following game must have a winner.  Place $6$ dots equally spaced on a circle on a piece of paper.
Player A has a red marker and Player B has a blue marker.
Players take turns connecting pairs of dots with line segments using their respective colored markers,
only one line segment between any two dots (therefore at most $15$ line segments will be drawn).
The winner is the first to connect three dots mutually with their respective color, that is, the first to create a monochromatic ``triangle''
in their marker's color:

3. Please prove or disprove: \emph{If $n \in \Z^+$, then $n^2 + n +41$ is prime.} 

4. 	Suppose $x$ is a positive integer with $n$ digits, say $x = d_1d_2d_3\cdots d_n$. In other words,
		$d_i \in \{0,1,2,\dots, 9\}$ for $1 \leq i \leq n$, but
		$d_1 \neq 0$.  Here's a definition: For $a, b \in \Z$, $a$ is a {\bf divisor} of $b$ if $b = ak$, for some $k \in \Z$.
		Please prove the following statement: \emph{If $9$ is a divisor of $d_1 + d_2 + \cdots + d_n$, then $9$ is a divisor of $x$.
