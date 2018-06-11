# trigonometry

# Why I wrote this?
  <ul>
  <li>
  Well, Python has its own standard library called `math` but I saw that it actually has wrong implementation of tangent function because when the input is math.tan(math.pi/2) the output is `1.633123935319537e+16` which is other way of saying `1.633123935319537 * 10^(16)` while this is totally false because tangent of 90 degree is undefined. So I wrote a trigonometric library which includes 6 trigonometric functions namely (sine, cos, tan, cot, cosec, sec).
  </li>
  <li>
    When I was a kid, I always feared trigonometry so I had to make myself believe that trigonometry isn't the doomsday from DC Comics. 
  </li>
  </ul>
  
  
# What are all the functions(methods)?
  <ul>
  <li>sine</li>
  <li>cos(cosine)</li>
  <li>tan(tangent)</li>
  <li>cot(cotangent)</li>
  <li>csc(cosecant)</li>
  <li>sec(secant)</li>
  </ul>
  
# How to use this?
  First things first, this was not made for scientists so you can directly input your measures in degrees.
  Later the program converts your degrees into radians and computes what it has to
  If you're already into trying this, here is how you "should" try this.
  You could actually give a degree measure either when instantiating or when calling the respected trig functions.
  
  <b> One way: </b>
  Example:
  ```python
  from trig import trigonometry
  trig = trigonometry(60)
  sine_value = trig.sine() # one way to get the value of sine
  ```
  
  <b> Other way: </b>
  Example:
  ```python
  from trig import trigonometry
  trig = trigonometry()
  sine_value = trig.sine(60)
  ```
  
  
# Thanks
  Mary Jane Sterling (Book author)
