# Calculus 1 Dictionary
## Limits
- #Limit the limit of a function is the value of the ouput as the input approaches, but does not reach, a given value. Given a function f, a fixed input x=a and a real number L, we say that f has a limit as x approaches a, and write the formula provided that we can make f(x) as close to L as we like by taking x sufficiently close (but not equal) to a.
  - $$\lim_{x\to a}f(x)=L$$
- no imaginary numbers in this class, keep it real
- #One-Sided-Limit
  - Left/Right limit shows the approached value from the left or the right ONLY.
  - $$\lim_{x\to A^-} \ \text{or} \ \lim_{x\to A^+}$$

## Derivatives
- #Derivate
  - Let f be a function and x = a where a is in its domain.
  - The derivate of f with respect to x evaluated as x = a, or written as
  - $$f'(a)=\lim_{h\to0}\frac{f(a+h)-f(h)}{h}$$
  - Provided the limit exists, the derivative is the slope of the tangent line at point (a, f(a)).
  - $$f'(a)=\lim_{x\to a}\frac{f(x)-f(a)}{x-a}$$
- #Derivative-Function
  - Let f be a function and x any value in its domain. We define the derivative of f, a new function called f' by:
  - $$f'(x)=\lim{h\to0}\frac{f(x+h)-f(x)}{h}$$
  - providing the limit exists.
- #Graphing-Derivative
  - Where f(x) is flat, f'(x)=0.
  - In each non-zero intervals, figure out the approximate slope of the steepest point and approximate a tangent line's slope. Plot that point and "curvily" connect it to your next-adjacent zero-points.
- #Direct-Substitution
    - Plug your actual limit into a function, either you get:
    - Valid answer, done
    - Non-zero over zero -> vertical asymptote
        - two up = inf
        - two down = -inf
        - one up one down = does not exist
    - rest -> indeterminate (need to rewrite)
- #Estimate-Derivatives
  - #Forward-Difference
    - $$\bar{V}_{[a, a+h]}=\frac{f(a+h)-f(a)}{h}$$
  - #Backwards-Difference
    - $$\bar{V}_{[a-h, a]}=\frac{f(a)-f(a-h)}{h}$$
  - #Central-Difference
    - $$\bar{V}_{[a-h, a+h]}=\frac{f(a+h)0-f(a-h)}{2h}$$
