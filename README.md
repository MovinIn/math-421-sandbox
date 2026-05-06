# Final
Prove a number is irrational using proof by contradiction.   
Understand max, min, inf, sup  

Let $$L$$ be the sup: 

$$
\forall \epsilon > 0 \exists s \in S st. L- \epsilon < s
$$

See that $$inf(S) = -sup(-S)$$

Completeness Axiom, Archimedian Property, Triangle Inequality, Density of the Rational Numbers.   

A sequence: $${(a_n)}_{n \ge 1}$$.   
Definition of the limit of a sequence: A sequence converges to $$L$$ if 

$$
\forall \epsilon > 0 \exists N \in N st. n \ge N \implies |a_n - L| < \epsilon
$$

Definition of the limit of a function: A function converges to $$L$$ at $$a$$ if 

$$
\forall \epsilon > 0 \exists \delta st. |x-a| < \delta \implies |f(x) - L| < \epsilon
$$

Definition of the derivative of a function: A function $$f$$ is differentiable at $$a$$ and equal to $$D$$ if

$$
\forall \epsilon \exists \delta st. |x-a| < \delta \implies | \frac{f(x)-f(a)}{x-a} - D| < \epsilon
$$

Extreme Value Theorem: If a function $$f$$ is continuous over the interval $$[a,b]$$, then the function realizes a maximum and minimum at least once within that interval.   

Intermediate Value Theorem: If a function $$f$$ is continuous over the interval $$[a,b]$$, then: 

$$
\forall m \in [f(a), f(b)] \exists c \in [a,b] st. f(c) = m
$$

Mean Value Theorem: If a function $$f$$ is continuous over the interval $$[a,b]$$ and differentiable over the interval $$(a,b)$$ then: 

$$
\exists c \in [a,b] st. f'(c) = \frac{f(b)-f(a)}{b-a}
$$

Rolles Theorem: A special case of Mean Value Theorem where $$f(a) = f(b)$$.   

Uniform Continuity: A function is uniformly continuous on domain $$D$$ if 

$$
\forall \epsilon > 0 \exists delta > 0 st. \forall x, y \in D |x-y| < \delta \implies |f(x) - f(y)| < \epsilon
$$

Integrability: A function $$f$$ is integrable over the interval $$[a,b]$$ if 

$$
\forall \epsilon > 0 \exists a partition P of [a,b] st. U(f, P) - L(f, P) < \epsilon
$$

Fundamental Theorem of Calculus (I): 

If $$g$$ is a continuous function over $$[a,b]$$ that is differentiable over $$(a,b)$$, and if $$g'$$ is integrable on $$[a,b]$$ then 

$$
\int_{a}^{b} g' = g(b) - g(a)
$$

Fundamental Theorem of Calculus (II): 

Let $$f$$ be a integrable function over $$[a,b]$$. For $$x \in [a,b]$$, let 

$$
F(x) = \int_{a}^{x} f(t) dt
$$

Then F(x) is continuous over $$[a,b]$$. If f is continuous at $$x_0 \in (a,b)$$, then $$F$$ is differentiable at $$x_0$$ and 

$$
F'(x_0) = f(x_0)
$$

