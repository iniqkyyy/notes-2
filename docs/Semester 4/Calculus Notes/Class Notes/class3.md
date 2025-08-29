# Calculus 1 Lesson 3
- finishing section 1.2 then doing 1.3
- all tech using now is same as before
## Section 1.2
### Approaches to Limits
- If you have a graph, look at where it seems to be going
- If you are doing it numerically, you can plug numbers that get closer to your value to notice a pattern
- For functions...
- #Direct-Substitution
    - Plug your actual limit into a function, either you get:
    - Valid answer, done
    - Non-zero over zero -> vertical asymptote
        - two up = inf
        - two down = -inf
        - one up one down = does not exist
    - rest -> indeterminate (need to rewrite)
### Limits Algebraically
- (a) is not EQUAL to 0/0, it has a FORM of 0/0
  - factor
  - $$\frac{x^2-1}{x-1}=\frac{(x-1)(x+1)}{x-1}$$
  - put an equals sign at the start of your line to show you're rewriting and not writing something new
  - $$=\lim_{x\to1}(x+1)\to1+1=2$$
- (b) has a FORM of 0/0
  - conjugate because there's a sqrt +- another term!
  - $$=\lim_{x\to0}(\frac{x}{\sqrt{x+1}-1})(\frac{\sqrt{x+1}+1}{\sqrt{x+1}+1})$$
  - don't expand numerator
  - $$=\lim_{x\to0}\frac{x(\sqrt{x+1}+1)}{x}$$
  - cancel x
  - $$=\lim_{x\to0}\sqrt{x+1}+1$$
  - direct sub
  - $$\sqrt{0+1}+1=2$$
- ONE OF THE NEXT TWO PROBLEMS WILL SHOW UP ON THE QUIZ ON WEDNESDAY
## Section 1.3
### Derivative at a Point
- #Derivate
  - Let f be a function and x = a where a is in its domain.
  - The derivate of f with respect to x evaluated as x = a, or written as
  - $$f'(a)=\lim_{h\to0}\frac{f(a+h)-f(h)}{h}$$
  - Provided the limit exists, the derivative is the slope of the tangent line at point (a, f(a)).
  - $$f'(a)=\lim_{x\to a}\frac{f(x)-f(a)}{x-a}$$
- Extra activity 1 (**b**)
  - $$g'(2)=\lim_{h\to0}\frac{g(2+h)-g(2)}{h}$$
  - write this out every time to show you know the definition
  - #Direct-Substitution will never work because the rise and run will always be zero, so it will always be in indeterminate form
  - $$=\lim_{h\to0}\frac{(3(2+h)^2-1)-(3\cdot2^2-1)}{h}$$
  - distribute
  - $$=\lim_{h\to0}\frac{3(4+4h+h^2)-12}{h}$$
  - factor
  - $$=\lim_{h\to0}\frac{12+12h+3h^2-12}{h}$$
  - factor out h and cancel out 12s
  - $$=\lim_{h\to0}\frac{h(12+3h)}{h}$$
  - cancel h and sub
  - $$12+3(0)=12$$
- work problems a and c on your own (answers are 4 and 1/3, more important to show work and don't use known shortcuts)
- 
