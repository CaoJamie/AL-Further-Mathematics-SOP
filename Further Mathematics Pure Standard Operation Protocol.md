# Further Mathematics Pure SOP

**IMPORTNT NOTES** Although this SOP tried to eliminate all difficulties to do further math pure question, there comes the necessaries which you should personally try at least 5-6 set of different past paper to get familiar with all the question type. The either or question is a particular hard one and sometimes you may find that they require more insight than practice. This SOP doesn't responsible for any kind of mistakes or omission during the production of the notes and suggest the candidate to do as much as past papers as possible to ensure they truly understand the approach.

## Complex Numbers

a complex number could be expressed by $a +bi = r(\cos\theta + i\sin\theta)$ for $r \geq 0$ , which is been taught as modular argument form in P3( Do notice that familiarity is required for the complex number part of P3)

By using Euler formula we can express $z = r(\cos\theta + i\sin \theta) = re^{i\theta}$

### Root of Unity

the root of unity can be expressed as:

$z^n =e^{i\theta*n} =(\cos\theta + i\sin\theta)^n = (\cos n\theta + i\sin n\theta)= 1$

$\theta = \frac{2\pi}{k}$ for $ k=0,1,2,...(n-1)$

solving other roots would require the additional r in the expression but the idea is similar

###De Moivre's Theorem

De Moivre's theorem(which you can prove by induction) state that $(\cos\theta + i\sin\theta)^n = \cos(n\theta) + isin(n\theta)$

this could be very useful because we can now evaluate:

$\Re {(\cos\theta+ i\sin\theta)^n} = \cos(n\theta)$  and $\Im{(\cos\theta + i\sin\theta)^n} = sin(n\theta)$, which is useful to simplify the high degree trigonometry expression in integration

Notice that the expression could also have binomial expansion, so some question would ask you: hence find the relationship for $\cos^n(\theta)$ and $\cos(n\theta)$

Another frequent testing point is the ability to convert the expression $(z^n \pm z^{-n})$

$z^n + z^{-n} = 2\cos(n\theta)$ and specifically $z^1 + z^{-1} = 2\cos(\theta)$

$z^n - z^{-n} = 2\sin(n\theta)$ and specifically $z^1 - z^{-1} = 2\sin(\theta)$

Notice you will also need to be able to binomial expand this expression in order to complete the question

Since the De Moivre's theorem require fluency in trigonometry, so here I list some might be useful notes:

* $\sin^2x + \cos^x = 1$
* $1 + \tan^2x = \sec^2x$
* $1+\cot^2x = \csc^2x$
* $\sin(-x) = -\sin(x)$
* $\cos(-x) = \cos(x)$
* $\tan(-x) = -\tan(x)$
* $sin(\frac{\pi}{2} - x) = \cos(x)$ 

## Implicit Differentiation

This is usually the case where it combines with parametric equation, so take care of doing those questions.

consider an equation:

$P(y) + P(xy) + P(x) = 0$ where $P(n)$ represents the polynomial related to n

by taking $\frac{d}{dx}[P(y) + P(xy) + P(x) ] = \frac{d}{dx}0$  we could obtain the result by partial fraction:

* the primary principal is to take y as the variable of x and by chain rule multiplying $\frac{dy}{dx}$ on it
* Notice for the product rule the same principle applies, so be careful to deal with the term such as $P(xy)$

if you want to obtain the second derivatives, the technique is to apply $\frac{d}{dx}$ towards the expression you obtain in the first step again, and plug in the value you obtain for $\frac{dy}{dx}$ with it.

For parametric equation or the formula that require you to do substitution, the process could be a little bit more difficult since it require you to conduct simplification, but remember the core principal demonstrated before, especially the application of chain rule $\frac{dy}{dx} = \frac{dy}{dt} * \frac{dt}{dx}$

## Differential Equation 

The general solution $y$ for an differential equation $a\ddot{y} + b\dot{y} + cy = f(x)$ can be obtained by finding $y = y_{C.F.} + y_{P.I.}$

### Complimentary Function

For the differential equation $a\ddot{y} + b\dot{y} + cy = f(x)$ , we can give the form of C.F. by examine roots of auxiliary equation.

auxiliary equation for the differential equation is $ak^2 + bk + c = 0​$

* 2 unique real root $k_1,k_2$, $y_{C.F.} = A\exp{k_1x}+B\exp{k_2x}​$
* 1 unique real root $k$, $y_{C.F.} = (A+Bx)\exp{kx}$
* 2 imaginary root $z = \alpha \pm i\beta $, $y_{C.F.} = \exp{\alpha x}(Asin\beta x + B\cos\beta x)​$

### Particular Integral

For the differential equation $a\ddot{y} + b\dot{y} + cy = f(x)$ , find the form of P.I. by giving identical expression of particular integral   $g(x)$ as $f(x)$

| $f(x)$                        | $g(x)$                        |
| ----------------------------- | ----------------------------- |
| $A\cos(kx) + B\sin(kx)$       | $C\cos(kx) + D\sin(kx)$       |
| $A\exp{kx}$                   | $B\exp{kx}$                   |
| $Ax^r + Bx^{r-1} + \dots + n$ | $Cx^r + Dx^{r-1} + \dots + m$ |

Substituting $y_{P.I.} = g(x),y'_{P.I.} = g'(x),y''_{P.I.} = g''(x)$ into the equation $a\ddot{y_{P.I.}} + b\dot{y_{P.I.}} + cy_{P.I.} = f(x)$ , solve the equation by equating the coefficient.

### General Solution and Particular Solution

Sum the particular integral and complementary function would lead to general solution y,

Substituting specific starting condition of x,y allow you to give particular solution

## Polar Coordinate

Under the SOP, the notation will be denoted with $(x,y)_{c} \longmapsto(r,\theta)_{p}$ as c stands for Cartesian and p stands for polar 

### Transformation

Transform the coordinate from Cartesian to Polar: 

$(x,y)_{c} \equiv (\sqrt{x^2 + y^2},\tan^{-1} \cfrac{y}{x})_{p}$

Transform the coordinate from Polar to Cartesian:

$(r,\theta)_{p} \equiv (r\cos \theta, r\sin \theta)_{c}$

### Sketch the graph

In the polar coordinate, the positive x axis is called initial line, and $\theta$ is the angle between initial line and the positive axis anticlockwise

for expression $r = f(\theta)$ take the table of the following value, plug in and calculate the result for r:

$\theta :=  0,\frac{\pi}{6},\frac{\pi}{4},\frac{\pi}{3},\frac{\pi}{2},\frac{2\pi}{3},\frac{3\pi}{4},\frac{5\pi}{6},\pi,-\pi,-\frac{5\pi}{6},-\frac{3\pi}{4},-\frac{2\pi}{3},-\frac{\pi}{2},-\frac{\pi}{3},-\frac{\pi}{4},-\frac{\pi}{6}$

Notice this should give a symmetrical $\theta$ samples around the axis, each quadrant includes 5 samples point(including points on axis), and commonly this should allow you to take the graph accurately enough

If taking two graph, calculate the potential position for which the graph are contact by equating $C_{1} = C_{2}$

If asked, takes the calculation of any stationary point by taking $\cfrac{dr}{d\theta}$

After getting results, neglect any negative r as definition for CIE don't require to sketch the r graph, and the domain for $\theta \in (-\pi,\pi]​$, but the question may asked for different value

### Noticeable Graphs

* Circle: $r = a, r = a\sin\theta, r = a\cos\theta$
* Straight Line: $r = a\sec\theta, r = a\csc\theta$
* Spiral:$r = a\theta$

### Common Symmetry

* $sin\theta$ is symmetric about $\theta = \frac{\pi}{2}$
* $\cos\theta$ is symmetric about $\theta = 0$

notice $\theta$ can be extend to any expression within those trigonometry identities

### Arc Length

The arc Length of the curve in polar coordinate on $r = f(\theta)​$ between $(r_1,\theta_1)​$ and $(r_2,\theta_2)​$ is given by the formula:

$l = \int^{\theta_1}_{\theta_2} \sqrt{r^2 + (\cfrac{dr}{d\theta})^2}d\theta$

Notice the curve must be continuous between the upper and lower bound for the integral

### Area

The area enclosed by the curve $r = f(\theta)$ between $(r_1,\theta_1)$ and $(r_2,\theta_2)$ is

$A= \cfrac{1}{2}\int^{\theta_1}_{\theta_2} r^2d\theta$

Notice the curve must be continuous between the upper and lower bound for the integral

## Further Integration

### Integration Skills

Apart from integration by part, substitution(happily most of the substitution in further math would come with the question so at least you would know your starting point) and partial fraction(which you should be familiar already in P3), some of the additional skills in further math is required:

sometimes you would notice there exist fraction that looks like these:

$\int \cfrac{1}{\sqrt{a^2 - x^2}}dx = arcsin(\cfrac{x}{a})$  which is clearly demonstrated to solve by having substitution of $x = a sin(x)$

and then solve with trigonometry identity $sin^2{x} + cos^2{x}=1$

$\int{\cfrac{1}{a^2 + x^2}}dx = \frac{1}{a}arctan(\frac{x}{a})$ which is similarly demonstrated to solve by having subsitution of $x = a tan(x)$ and then solve with trigonometry identity $1+tan^2{x} = sec^2{x}$

if you find you are unfamiliar with this part of the context, reference to MF10 formula sheet for help

and some small reminder from P3(you should recall using partial fraction to solve this question):

$\int{\cfrac{1}{a^2 - x^2}}dx = \frac{1}{2a} ln \left|{\cfrac{a+x}{a-x}}\right|$

$\int{\cfrac{1}{x^2-a^2}}dx = \frac{1}{2a} ln \left|\cfrac{x-a}{x+a}\right|$

### Reduction Formula

This question is very characteristic in the further math test because usually the question will contains the expression such as $I_n= \int f(x) * g(x)'dx$

In this case the expression is usually solve by using integration by parts which will then give the formula in

so what we need to do is to takes integration by parts and obtain:

$I_n = [f(x)g(x)] - \int{f(x)'g(x)}dx$, where the expression usually evaluate $\int f(x)'g(x) dx$ to another $I_k$ related to $I_n$, which you could then related the reduction formula to$I_n = f(x) + P(x)I_k$, or something similar to this. 

The question usually goes without a hence, but sometimes you would be ask to derive some expression and then start working from there. For the expression that contains derivatives it is not a bad idea to try at least integrate the both side.

Usually the question would ask you to demonstrate a certain value for $I_n$, such as $I_5$, in which you should demonstrate all the process for calculating intermediate $I_k$ to prevent mark loss

### Mean Value

This is required by the syllabus(although not tested as often as you might expected). The actual technique usually only worth a small portion of your mark, but the formula should be remember by heart:

 $$\bar{f} = \cfrac{1}{b-a} \int_a^b f(x) dx$$

### Arc Length

The arclength for a equation $y = f(x)$ could be expressed by: 

$$l = \int{\sqrt{1 + (\frac{dy}{dx})^2} dx}$$

when encountering parametric equation, you could change the equation into:

$$l = \int{\sqrt{{\frac{dy}{dt}}^2 + {\frac{dx}{dt}}^2}}dt$$

notice in the case of parametric equation you need to check the upper and lower bond to ensure that the limit had been changed from x to t.

Plug in the number and you would obtain the answer. Notice due to the appearance of square root, it is usual that you can simplify this using the skills of polynomial or by using the trigonometry identities(which is more often to appear compare with the previous one)

### Surface Area

The surface area of a curve enclosed by the axis could be expressed as this:

Enclosed with x axis: $A = \int 2\pi y ds​$, where $ds = \sqrt{1+{\frac{dy}{dx}}^2}dx​$

Enclosed with y axis: $A = \int 2\pi x ds$,  where $ds = \sqrt{1+{\frac{dx}{dy}}^2}dy$

notice for the rotation around the y axis would require you to take the inverse function so that $x = h(y)​$ 

### Centroid

These questions are rarely asked, but when they appeared it is usually in one of those either or question. 

It's still on the syllabus and there were records where this knowledge was required to apply into the question 1-10. I suggest taking some time to remember the formula in case you need it.

For 2D region:

$\bar{x} = \cfrac{\int{xy}dx}{\int{y}dx}$  and  $\bar{y} = \cfrac{\frac{1}{2}\int{y^2}dx}{\int{y}dx}$

Notice in the case of a parametric equation you may need to substitute $dx$ with expression of $dt$ by using $dx = \frac{dx}{dt} * dt$ and **changing** the upper and lower bond with the appropriate t value

For 3D region (which is even less likely to be tested):

$\bar{x} = \cfrac{\int_v{x}dv}{\int_v dv}$ and $\bar{y} = \cfrac{\int_v{y}dv}{\int_v dv}$

## Curve Sketching

Here are the standard procedure to sketch the curve (which you should follow at most of the time)

### Horizontal and Vertical Asymptote

Notice that usually the first few mark is awarded towards determine the asymptote.

In this case you should easily obtain the horizontal asymptote for $y = f(x)$ by calculating the following limit:

$\lim_{x->\infty} y $ and $\lim_{x-> - \infty} y $

simpliy divide the highest degree from the above part of the fraction and obtain the answer. Notice if the upper part is higher than it tends to $\infty$ and if it is lower than it tends to 0. If the  degree is the same then it tends to the coefficient of the highest degree

notice in most of the time the result would provide the same, but you do need to double check it to make sure it is actually true

For the vertical asymptote, I suggest you only search them when the formula for $y = f(x)$ could be simplify into $f(x) = \cfrac{h(x)}{g(x)}$, which in this case you should obtain the result by calculating for $g(x) = 0$, i.e. the lower part of the fraction equals 0

### Oblique Asymptote

Notice that in some of the exam you would found that the expression$y = f(x)$ could be simplify to the following result $f(x) = \cfrac{x^n+1 + x^n + \dots + c}{x^n + \dots + 1}$, which means that the higher part of the fraction is a polymer of x that is one degree higher than the lower part, you should not seek the horizontal asymptote but instead search for the oblique asymptote in the form of $y = ax+b$

so consider the expression

$y = \cfrac{ax^2 + bx + c}{ex+f}$

we want to evaluate its into the form $y = mx + k + O(1/x)  +\dots$

hence we would use the long division in this case and only take the terms for $mx + k$ since the rest is 0 under the limit as $x \rightarrow \infty$

### Stationary Point

The next important set of point to consider is the stationary point. This should be simple to obtain because you would only need to find the point for $\frac{dy}{dx} = 0$ 

Remember to indicate those point on the sketch and state that they are the stationary point

In some cases you may need to find the nature of the stationary point by evaluating $\frac{d^2y}{dx^2}$ 

recall that:

$\frac{d^2y}{dx^2} > 0 \implies minimum$

$\frac{d^2y}{dx^2} = 0 \implies point \space inflextion$

$\frac{d^2y}{dx^2} < 0 \implies maximum$

### Intersection with Axes

The x intersection and y intersection is always required for sketching, by simply plug in $y=f(x)$ with:

$f(0) \rightarrow (0,f(0))$ and $f(k) = 0 \rightarrow (k,0)$

### Sketching Techniques

after drawing the dash line for the asymptote and label stationary point, here is a useful trick for quick sketching:

starting from$-\infty$ , consider the sign of the expression $f(x) = \frac{h(x)}{g(x)}$ , by using the point $k+\epsilon, k-\epsilon$ around the point $x = k$ so that you would have a rough understanding of the trend of the function

Combine with the previous result you could sketch the curve easily

## Series

### Standard Result

$\sum{r} =\frac{1}{2}n(n+1)$

$\sum r^2 = \frac{1}{6}n(n+1)(n+2)$

$\sum r^3 = \frac{1}{4}n^2(n+1)^2$

by separating the summation into the linear combination of the standard result you would be able to easily obtain a result 

### Method of Difference

if you see some expression such as $\sum f(p) - f(q)$ which in particular include form such as partial fraction, or other similar patterns

you can expand it to something similar to this(the precise number is based on **question**): 

 $= f(1) - f(2) - f(2) + f(3) -\dots + f(n-1) - f(n)$

and hence you would get by elimination

$ = f(1) - f(n)$, which gives the simplify solution to the question

the pattern is that there is consecutive $f(n+k) - f(n-k)$ appears into the extended form, and usually the question would give you a hint if the method is relatively difficult to found

### Convergence

the degree of convergence which CIE requires is by analyzing the analytic solution to the sums as $n \rightarrow \infty$ and see if this converge to a certain number.

Specifically, to consider the convergence of a series, you can do this:

$$\lim_{n\rightarrow \infty} \sum^n_{r=1} a^r$$ 

Check if that analytic formula tends to a specific limit.(a small trick would be to at least check $lim_{n\rightarrow \infty} a^n$ has a limit otherwise the series diverge)

## Proof by Induction

Proof by induction follow a standard procedure which you should clearly demonstrate your understanding of this format onto the paper:

1. State the statement: $H_k : P(k)​$
2. show that $H_1$ is true
3. assume $H_k$ is true for some number $n\in \N$  or $n \in \Z^+$
4. show that $P(n+1)$ is true by the assumption that $H_n$ is ture
5. state that $H_n \implies H_{n+1}$
6. state that by the principal of mathematical induction(PMI), the statement is true for all $n\in \N$  or $n \in \Z^+$

Notice most of the mathematical induction question would be related to number theory or calculus expression, which you should be able to solve with some algebra manipulation(such as taking $n = a*k​$ for those divisible question), but for some of those series question, you may need to think it carefully or seek help directly from the Maclaurin’s expansion in MF10

## Matrix and Determinant



## Vector Geometry



## Vector Space

Vector space is a relatively abstract topic in the further math so it is consider difficult first encounter. However, CIE also consider about this situation so the question usually set is easier to solve compare with the other exam board. 

### Axioms of Vector Space

### linear independent

### subspace

### Spanning a space

### Range space

## Polynomials

### Relations Between Roots and Coefficient

For a general polynomial $P(x) = ax^n + bx^{n-1} + cx^{n-2} + \dots + d​$ , it will have root $\alpha, \beta, \gamma \dots​$, then we would be able to obtain the following result easily:

* $\sum \alpha = -\cfrac{b}{a}$
* $\sum \alpha\beta = \cfrac{c}{a}$
* $\sum \alpha \beta\gamma = -\cfrac{d}{a}$
* $\dots$  Notice the pattern can be extended to even higher degree by repeating this pattern for a specific equation

These results should be carefully remembered. Notice that the sum notation actually means symmetrical sums, which means all of the possible permutation of the variable should be sum. For example, $\sum \alpha \beta ​$ means actually to have $\alpha \beta + \alpha \gamma + \beta \gamma​$ So make sure you calculate the sum correctly. By summing these value and getting the equation together, we can find the value of coefficient.

Other than that there are other formula (Newton's Sum) that would be useful in the context of questions, which you should remember clearly(Notice MF10 doesn't contain those formula so you should be caution to remember them clearly)

* $S_1 = \sum \alpha = -\cfrac{b}{a}​$
* $S_2 = \sum{\alpha}^2 = (\sum \alpha)^2 - 2\sum \alpha \beta​$
* $S_3=\sum \alpha^3 = (\sum \alpha)^3 - 3\sum \alpha \beta\sum\alpha+3\sum \alpha\beta\gamma$
* $S_4=\sum \alpha^4  = (\sum \alpha)^4 - 4\sum \alpha\beta(\sum \alpha)^2 +4\sum\alpha\beta\gamma\sum\alpha+2(\sum\alpha\beta)^2 - 4\sum\alpha\beta\gamma\delta​$ [usually we would recommend that you obtain it via substitution or recurrence instead due to the difficulties for remembering it]
* $ S_{-1}=\sum \cfrac{1}{\alpha} = \cfrac{\sum \alpha \beta}{\sum \alpha \beta\gamma}$

### Method of Substitution

During the exam, there exists some question which ask you to find for example, equation suitable for $\cfrac{1}{\alpha},\cfrac{1}{\beta},\cfrac{1}{\gamma}$ or similar component form from the original roots of the equation.  Otherwise, the substitution would be directly given and you will be required to carry out algebraic manipulation to form a new equation, by for example, substituting  for instance, $y = \cfrac{1}{x}, y = x^2,  y = x^4$ into the original polynomial of $P(x)$ and obtain a new equation from it. 

Notice sometimes you would have equation containing $y^\frac{1}{2}$, in this way you should move all the integer power to one side and fractional power to other side, having suitable power(for example power of 2 in this case) for both side and hence get the new equation.

### Method of Recurrence

given a polynomial $P(x) = ax^n + bx^{n-1} + cx^{n-2} + \dots + d$, we know by **factor theorem** that if $x = \alpha,\beta,\gamma,\dots$ is the root of polynomial,  then:

* $a\alpha^n + b\alpha^{n-1} + c\alpha^{n-2} + \dots + d = 0​$
* $a\beta^n + b\beta^{n-1} + c\beta^{n-2} + \dots + d = 0$
* $a\gamma^n + b\gamma^{n-1} + c\gamma^{n-2} + \dots + d = 0$
* $\dots$

summing all of them, we would easily obtain the relationship: $aS_n + bS_{n-1} + cS_{n-2} + \dots + n*d = 0​$

this allow us to have another approach to obtain $S_n$

Notice, this relationship $aS_n + bS_{n-1} + cS_{n-2} + \dots + n*d = 0$ can be extend to any power of S, for example the same equation implies also $aS_{n-1} + bS_{n-2} + cS_{n-3} + \dots + n*dS_{-1} = 0$ since you would find that dividing a x from the original equation means the formula will still hold.