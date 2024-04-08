# Math Dictionary
## Roots
* #Even-Odd-Root even roots cannot be negative (not real), odds can be.
* #Pos-Neg-Root when solving roots 
$$\begin{cases} \sqrt[n]{x} = |x| & \text{if} & x \to \text{even} \\ \sqrt[n]{x} = x & \text{if} & x \to \text{odd}\end{cases}$$

## Notation
* #Interpret-In-English Always include input title, output title, use a word to describe the change in value ex. (increased, decreased)
* #Union The symbol for to unionize two sets is : 
"$$\cup$$"
for example : 
$$(1,3)\cup(5,7)$$ 
* #Interval-Notation Method to show inequality (for domains, etc.). Square bracket shows "inclusive", parenthesis shows "exclusive" and infinities always get parenthesis, ex.
$$(1\leq x\lt \infty)\to[1, \infty)$$ 

## Graphing
* #Relation is the *input/output* or *mapping* of a graph, ex. 
$$\{(2,3), (3, 4), (5,6)\}$$  
* #Domain is the set of all *input* values, ex. 
$$\{2, 3, 5\}$$  
* #Range is the set of all *output* values, ex. 
$$\{3, 4, 6\}$$  
* #Function is the relation of an input/output pair where every input has a single unique output. Also a "Rule" that assigns an output to a given input.
* #VerticalLineTest If a vertical line on a graph crosses two data points, the data points are not a result of the function.
* #Function-Variables Output is always a function of Input, Output (y) is dependant, Input (x) is *in*dependant.
* #Function-Notation 
$$f(x) \; \text{will **never** be multiplication. Say "f of x".}$$
* #Net-Change Is the change in output between two inputs, subtracting the second value from the first.
* #Set-Builder-Notation to define sets using special characters, ex. 
$$\{x|;x \leq 6,x\neq3\}$$  
* #Piecewise-Defined-Function is a way of describing functions using rules, for example :  
$$f(x)=\begin{cases} x^2 & \text{if} &x<1 \\ x + 1 &\text{if}&x\geq 1\end{cases}$$
* #Six-Basic-Functions
    * Constant Function, horizontal line ex. 
    $$f(x) = 3$$  
    * Identity Function, diagonal line ex. 
    $$f(x)=x$$  
    * Square Function, "U" shape ex. 
    $$f(x)=x^2$$  
    * Cube Function, "S" shape (negative input = exponential negative output, positive input = exponential positive output) ex. $$f(x)=x^3$$  
    * Absolute Value Function, "V" shape ex. 
    $$f(x)=|x|$$  
    * Square Root Function, gentle curve, starting at 0 #Pos-Neg-Root ex. 
    $$f(x)=\sqrt{x}$$  
* #Average-Rate-Of-Change or #ARC describes how *quickly* the function increases or decreases over an interval. Also shown as the slope between two points. e.g: 
$$\large\newline\frac{\text{net change in y}}{\text{change in x}}= \frac{f(b) - f(a)}{b-a}=\frac{y_2-y_1}{x_2-x_1}$$
* #Secant-Line is the #Average-Rate-Of-Change in an interval. Draw a triangle showing rise/run in the interval and the hypotenuse will be the secant line.
* #Linear-Function are functions with a *constant* (not average) Rate of Change. A line on a graph.
* #Point-Slope-Form is the equation behind a #Linear-Function given a point on the line and the slope of the line. $$y-y_1=m(x-x_1)\;\text{where the point is}\;(x_1, y_1)\;\text{and the slope is}\;m$$
* #Slope-Intercept-Form is the equation behind a #Linear-Function given the slope and y-intercept of the line. $$y=mx+b$$ where $$m$$ is the slope and $$b$$ is the y-intercept.
* #Interpret-Yint-Slope y-intercept and slope in English.
  * Y-int : *When [x value] is 0, [y value] is [y-intercept]*

  * Slope : *When [x value] increases by 1, [y value] [increases/decreases] by [slope]*

* #Horizontal-Vertical-Line the function to show a Horizontal line is $$x = a$$ and a Vertical line is $$y = b$$.

## Quadratics and Parabolas

* #Quadratic is a function that produces a parabola (a mirrored curve), has three forms but is generally $$f(x)=ax^2+bx^1+cx^0$$
* #First-Second-Differences first differences is the change in $$y$$ when $$x$$ increases by 1, second differences is the change in first differences. Quadratic functions has a non-linear first difference (cannot cross the vertex during this comparison), but a linear second difference.
* #Discriminant is the section of the quadratic formula underneath the square root, if the discriminant is positive then there are two x-intercepts, if it is 0 then there is one x-intercept, and if it is negative there are no real solutions. $$D = b^2-4ac$$
* #Quadratic-Forms
  * #General-Form is the form $$ax^2+bx+c$$ where $$(0,c)$$ is the y-intercept of the parabola. 
  * #Factored-Form is the form $$a(x-m)(x-n)$$ where $$m$$ and $$n$$ are the x-intercepts of the parabola.
  * #Standard-Form is the form $$a(x-h)^2+k$$ where $$(h, k)$$ is the #Vertex of the parabola.
* #Vertex is the maximum or minimum of a parabola, depending on which way it opens.
  * #Factored-Form-Vertex the vertex of a #Quadratic in #Factored-Form is $$a(x-m)(x-n) \to (\frac{m+n}{2}, f(\frac{m+n}{2}))$$
  * #General-Form-Vertex the vertex of a #Quadratic in #General-Form is $$(\frac{-b}{2a},f(\frac{-b}{2a}))$$
  * #Standard-Form-Vertex the vertex of a #Quadratic in #Standard-Form is $$(h,k)$$
* #Stretch-Compression-Factor is $$a$$ in a #Quadratic, and defines how stretched or compressed the parabola is. ex. a quadratic with $$a=2$$ would be four times as steep as one with $$a=1/2$$.
* #Standard-Form-Graphing
  * For $$a(x-h)+k$$
    * Change in $$a$$ changes the #Stretch-Compression-Factor.
    * Change in $$h$$ moves the #Vertex of the parabola horizontally from $$(0, 0)$$ (opposite to intuition, since formula is $$x-h$$).
    * Change in $$k$$ moves the #Vertex of the parabola vertically from $$(0, 0)$$ (same as intuition, since fornula is $$+k$$).
* #General-Form-Graphing
  * For $$ax^2+bx^1+cx^0$$
    * Use the #General-Form-Vertex to plot the #Vertex of the parabola.
    * If $$b^2-4ac \geq 0$$ then find the x-intercepts and plot them.
* #Factored-Form-Graphing
  * For $$a(x-m)(x-n)$$
    * Use the #Factored-Form-Vertex to plot the #Vertex of the parabola.
    * Plot the x-intercepts using $$m$$ and $$n$$.

## Polynomials

* #Polynomial-Function is a sum of monomials e.g : $$a_n x^n$$ where $$n$$ is a positive whole number.
* #Polynomial-Degree is the largest exponent of $$x$$ in a #Polynomial-Function.
* #Leading-Coefficient is the coefficient of the largest exponent of $$x$$.
* #Polynomial-X-Intercepts a polynomial of degree $$n$$ can have up to $$n$$ x-intercepts, solved by setting numerator equal to 0.
* #Polynomial-Y-Intercepts a polynomial's y-intercepts are found by setting $$x=0$$ and solving for $$f(x)$$.
* #Graphing-Polynomial is based on the #Polynomial-Degree and the #Leading-Coefficient. If the LC is positive, both ends want to open up, if the Degree is odd it will swap the left opening.
  * Degree is even :
    * Leading Coefficient is positive : Both ends open up.
    * Leading Coefficient is negative : Left end is flipped, opens down.
  * Degree is odd :
    * Leading Coefficient is positive : Both ends open down.
    * Leading Coefficient is negative : Left end is flipped, opens up.
* #Asymptote a Horizontal or Vertical asymptote is a line that the graph of a function gets closer and closer to (vertical cannot cross, horizonal can cross). A function has a Vertical Asymptote $$x=a$$ if $$y\to\inf\lor-\inf$$ as $$x\to a$$ from either side.
* #Solving-Vertical-Asymptotes factor the polynomials, simplify if possible, then find values of $$x$$ that make the denominator = 0. x-intercepts can also be solved as only the numerator = 0 since the denominator cannot equal 0.
* #Solving-Horizonal-Asymptotes if the #Polynomial-Degree of the numerator is **equal to** the degree of the denominator, the Horizontal #Asymptote is equal to the ratio between the #Leading-Coefficient of the top and bottom polynomials. 
  * When the degree of the numerator is **less than** the degree of the denominator, the horizontal asymptote is at $$y=0$$.
  * When the degree of the numerator is **greater than** the degree of the denominator, there is *no* horizontal asymptote.
* #Solving-Negative-Exponent rational equations.
  * Try to clear the fraction by making a common denominator and/or making the whole thing equal 0.
  * $$5x^{-2}+x^{-3}=0 \;\;\to \;\;\frac{5}{x^2}(\frac{x}{x}) + \frac{1}{x^3} = 0 \;\;\to\;\; \frac{5x+1}{x^3}=0$$

## Exponential Growth

* #Difference-Quotient is the formula to calculate the #Average-Rate-Of-Change of $$f(x)$$ over the period $$h$$. $$\frac{f(x+h)-f(x)}{h}$$
* #Exponential-Growth is the formula of growth when the variable $$x$$ is in the exponent. $$f(x)=Ca^x$$ where $$C$$ is the initial value of $$x$$, $$a>1$$ is the growth factor, and $$x$$ is the number of time periods that have passed.
* #Exponential-Decay is the same formula and values as #Exponential-Growth except $$a<1$$ so instead of growing it decays.
* #Calculating-Exponential-Growth-Decay for $$f(x)=Ca^x$$, $$C$$ is the initial value or $$f(0)$$, $$a$$ is calculated with either #Growth-Rate or $$a=1+r$$ with $$r=\frac{2nd-1st}{1st}$$
* #Growth-Rate is the percent growth between time $$n$$ and time $$n+1$$. Where $$g$$ is the first value and $$h$$ is the second value $$r=\frac{h-g}{g}$$
* #Growth-Factor is $$a$$ in the #Exponential-Growth formula, represented as $$a=1+r$$ where $$r$$ is the #Growth-Rate. Easier to understand as if the growth rate is 20%, multiplying a number by 20% makes it smaller, you need to add the base 100% to make it 120% to make the function grow rather than shrink.
* #Solving-Exponential-Graph solve the equation $$f(x)=Ca^x$$ by plugging in the inital value ($$C$$) and a point ($$x,f(x)$$) and solving for $$a$$.
* #Relate-The-Bases use the base number $$b$$ to refactor exponential equations, eg.
  * $$b^{n}b^{m}=b^{n+m}$$
  * $$\frac{b^{n}}{b^{m}}=b^{n-m}=\frac{1}{b^{n-m}}$$
  * $$(b^n)^m=b^{nm}$$
  * $$b^{-n}=\frac{1}{b^n}\;\;\&\;\;\frac{1}{b^{-n}}=b^n$$
  * $$(ab)^n=a^{n}b^{n}\;\;\&\;\;\bigg(\frac{a}{b}\bigg)^{n}=\frac{a^n}{b^n}$$
  * $$\sqrt[n]{b}=b^{1/n}$$
