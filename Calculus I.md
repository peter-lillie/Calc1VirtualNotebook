# Calculus 1
Professor Jenna Reis
Fitchburg State University
MATH 2300-02 
Notes by Peter Lillie
## 1.1 Introduction to Limits
###  Standard Function: $$\lim_{x \to a} f(x) = L$$
<b><i>The Idea:</b></i> Approximate $f(1)$ without plugging in $x = 1$
<b><u>EX: Basic Function</u></b>
$$ f(x) =x^2+2x $$
Check numbers to the right and left of the $x$ value, in order to see where $f(x)$ <i>should</i> be. (Assuming it existed)
$x$ | $f(x)$
- | -
$.9$ | $2.61$ 
$.99$ | $2.9601$
$.999$ | $2.996$

$$ \lim_{x\to1} f(x) = 3 $$
In this case, it is easy to see where the $x$ value (or limit) should be, later on however, this will not be as easy to discern.

<b><u>EX: Rational Function</u></b>
$$f(x)=\frac{(x-2)(x+3)}{x-2} $$
What "should" $f(x)$ be?
$$ \lim_{x\to2}f(x)=?$$
<b>In English</b>
As x approaches 2, what does y approach?
$x$ | $f(x)$
- | -
1.9 | 4.9
1.99 | 4.99
1.999 | 4.999
<b><i>*Def:</b></i>
Suppose $f(x)$ exists on some interval around $x=a$ (not necessarily at $a$) If the values of $f(x)$ get arbitrarily close to $L$ as the $x$ values approach $a$ then we write: $$ lim_{x \to a}f(x)=L$$
<i>Tables can be frustrating to write for each limit. Graphs make understanding limits easier.</i>
![Line Graph w/Hole At (2, 5)](https://lh3.googleusercontent.com/ThNWKCLhQS1Sa9TnUN58Lr5V8hXgG7IFF_EYskr54otvGEpgAhywAyD18BFLQA5G2LeEkyVwPJ1E "Line Graph w/Hole At &#40;2, 5&#41;")
In the Graph above, we see that as $x$ approaches 2, $y$ gets closer to 5. Hence: $\lim_{x \to 2} f(x)=5$
<b><i>Rule:</b></i>
$L$ must be the limit from both sides of $a$. If the two sides are not equal, or do not exist, then $L = DNE$ (Does not exist) DNE is a valid solution.
<b><u>EX:</b></i>
![A Limit that DNE](https://lh3.googleusercontent.com/595qWL5TTu5w77_0OsFCIppi6M1FUhIFTunE4ThmLuklbMFomXSUWRdveCGPhSkVqIIM5q1NC4tE "DNE Example 1")
In this case: $$\lim_{x \to a}f(x)=DNE$$ This is because the $x$ values on the left do not move towards the same number as the $x$ values on the right. This will be covered more in depth later on.
<b><u>EX:</b></i>
![A Second example of limit = DNE](https://lh3.googleusercontent.com/ds4BVTLdNq-uNMAhoEGTfsMh1-sRBxKVmfv1VgbnOinTueeF0x5b8EJJ7Uc-VOzg0unBAGQQGmBX "DNE Limit EX 2")
In this case: $$\lim_{x \to a}f(x)=DNE$$ Because there are no $x$ values on the right of $a$.
## Appendix A: Glossary
$\to$: approaches
$\lim$: limit
$a^+$: values to the right of $a$
$a^2$: values to the left of $a$
## Appendix B: Formulas
<i>Limits Formula:</i>
$$\lim_{x \to a}f(x)=L$$


> Written with [StackEdit](https://stackedit.io/).
