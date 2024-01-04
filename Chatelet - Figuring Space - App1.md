
# Appendix 1: Note on Quaternions

A quaternion is an ordered quadruplet $q=(x_0,x_1,x_2,x_3)$.

An *addition* can easily be defined:

(**1**) $(x_0,x_1,x_2,x_3) + (x_0',x_1',x_2',x_3') = (x_0 + x_0',x_1+x_1',x_2+x_2',x_3+x_3')$

as can a *multiplication* by a scalar (a real number) corresponding to changes of level ('dilatations'):

(**2**) $\lambda (x_0, x_1, x_2, x_3) = (\lambda x_0, \lambda x_1, \lambda x_2, \lambda x_3)$

These operations make it possible to write quaternions in the form:

$$q=(x_0\textbf{1}, x_1\textbf{i},x_2\textbf{j},x_3\textbf{k}) $$
where
$\textbf{1} = (1,0,0,0)$
$\textbf{i} = (0,1,0,0)$
$\textbf{j} = (0,0,1,0)$
$\textbf{k} = (0,0,0,1)$

The quaternions of the form $(x_0,0,0,0) = x_0\textbf{1}$ are said to be 'real' ('temporal' according to Hamilton) and can be positive or negative; we will speak of the straight line associated with $\textbf{1}$. 

The quaternions of the form $(0,x_1,x_2,x_3)$ are said to be 'pure' (or 'spatial': these are the ones that represent space according to Hamilton). In particular, the elements $\textbf{i, j, k}$ are said to be 'spatial units'. 

The foregoing remarks lead us to decompose a quaternion by the formula:

(**3**) $q = x_0\textbf{1} + x_1\textbf{i} + x_2\textbf{j} + x_3\textbf{k} = (x_0,\vec{V})$

where $x_0$ is the 'scalar' part and $\vec{V}$ the 'vectorial' part.

We can define a multiplication $\times$ of quaternions, which would be distributive in relation to the preceding addition and compatible with dilatations:

$$ \lambda,q \times q' + (\lambda,q) \times q' = q \times (\lambda, q')$$
The formula of $\times$ being complicated, we will not give it here, but we should observe that:

(a) this multiplication is not generally commutative;
(b) non-zero quaternions (different from $(0,0,0,0)$) admit an inverse for $x$;
(c) it coincides with multiplication of real numbers for the elements of the real straight line;
(d) $\textbf{1} \times q = q \times \textbf{1}$ for all quaternions;
(e) 
$\textbf{i} \times \textbf{j} = -\textbf{j} \times \textbf{i} = k$
$\textbf{j} \times \textbf{k} = -\textbf{k} \times \textbf{j} = \textbf{i}$
$\textbf{k} \times \textbf{i} = -\textbf{i} \times \textbf{k} = \textbf{j}$
$\textbf{i}^2 = \textbf{j}^2 = \textbf{k}^2 = -\textbf{1}$
more generally: if $q = (0,x_1,x_2,x_3)$ is 'pure' or 'spatial', $q^2 = q \times q = (-[x_1^2 + x_2^2 + x_3^2],0,0,0)$. The square of spatial quaternions is *negative*. Moreover, the property of 'negative square' *characterizes* spatial quaternions;
(f) if $q$ an $q'$ are spatial quaternions,
$q \times q' = q' \times q$ if an only if $q$ and $q'$ are 'parallel' ($q=\lambda q'$ with $\lambda$ real);
$q \times q' = -q' \times q$ if and only if $q$ and $q'$ are 'perpendicular';
(g) the 'spatial units' $\textbf{i,j,k}$ constitute a trirectangular trihedron and swap place through *rotations* associated with multiplication (a particular case of the 'perpendicular torsion' of figure 25, p. 174).

