---
layout: default
title: "ME205: Numerical Methods for Engineers"
course_description: "A review of the numeric methods most useful for engineers, with particular emphasis on numbers and binary systems, numerical differentiation, linear algebra, solving non-linear systems, regression and optimization, ordinary differential equations, and fourier and finite element methods."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Solution of Nonlinear Equations** <span id="3"></span> 
**You have already encountered this topic in* [*ME101: Introduction to
Mechanical Engineering*](http://www.saylor.org/courses/me101/)*; you may
wish to review section 3.4.2 of that course.  In this unit you will
examine the topic in more detail and work through several more examples
using established techniques.*  
    
 *For motivation, you may wish to refer to the introduction of this
course. Consider that you have an equation of the form f(x) = ax^2
/[(bx^3  + c sin(dx) + f ln(x]). As part of an ongoing effort you need
to find the zeros of this equation several times per day for different
values of a, b, c, d, and f.  In particular, you need to find the zero
near a value of x = m.  The values of a, b, c, d, and f are known but
change hourly.*  
    
 *One approach to finding the zero near m, would be to plot the
expression as a function of x near m and visually inspect the resulting
plot; if necessary, one could zoom in on the area of interest in order
to evaluate the zero with more precision. This process is, however,
expensive because it requires human intervention. It is more cost
effective in many situations to have a machine evaluate the zero near m
with user-defined precision.*  
    
 *Note that we have limited the problem here to finding **a zero** near
m. To find all zeros is a much more difficult problem and is beyond the
scope of this unit. *  
    
 *The methods in this section are closely related. As you study the
resource materials methods, seek to find similarities and differences
between the methods. You may wish to refer to Unit 2 on numerical
differentiation as you study the secant method. **

**Unit 3 Time Advisory**  
Time Advisory: This unit will take you approximately 15 hours to
complete.  
  
 ☐    Subunit 3.1: 5 hours  
  
 ☐    Subunit 3.2: 10 hours  
  
 ☐    Sub-subunit 3.2.1: 7 hours

<span id="cke_bm_570S" style="display: none; "> </span>☐    Web Media: 2
hours

<span id="cke_bm_563S" style="display: none; "> </span><span
id="cke_bm_564S" style="display: none; "> </span>☐    Reading: 4 hours  
  
 ☐    Assessment: 1 hour

☐    Sub-subunit 3.2.2: 3 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Describe situations in which numerical solutions to nonlinear
    equations are needed.
-   Implement the bisection method for solving equations.
-   List advantages and disadvantages of the bisection method.
-   Implement both Newton-Raphson and secant methods.
-   Describe the difference between Newton-Raphson and secant methods.
-   Demonstrate the relative performance of bisection, Newton-Raphson,
    and secant methods. 

**3.1 Bisection Method** <span id="3.1"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s “Background of Bisection Method,” “Algorithm of
    Bisection Method,”, “ Example of Bisection Method,” and “Advantages
    & Drawbacks of Bisection Method”**
    Links:  University of South Florida: Holistic Numerical Methods
    Institute’s “[Background of Bisection
    Method](http://numericalmethods.eng.usf.edu/videos/youtube/03nle/bisection/bisection_03nle_background.html),”
    “[Algorithm of Bisection
    Method](http://numericalmethods.eng.usf.edu/videos/youtube/03nle/bisection/bisection_03nle_algorithm.html),”
    “[Example of Bisection
    Method](http://numericalmethods.eng.usf.edu/videos/youtube/03nle/bisection/bisection_03nle_example.html),”
    and “[Advantages & Drawbacks of Bisection
    Method](http://numericalmethods.eng.usf.edu/videos/youtube/03nle/bisection/bisection_03nle_advantages.html)” 
    (YouTube)  
        
     Instructions: Please view these four video lectures as an
    introduction to the topic of bisection method.  You will have a
    chance to review written descriptions in more detail later on in
    this subunit.  The total run time for these videos is approximately
    35 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Bisection Method”**
    Links:University of South Florida:Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Bisection
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the text with particular attention to the
    advantages and disadvantages of the method.  You may wish to
    consider how the method might perform, if there were a discontinuity
    in the expression of interest. (12 pages)  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Bisection Method”**
    Links: University of South Florida:Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Bisection
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.1-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Complete the entire multiple choice quiz.  Refer to
    “Textbook Chapter of Bisection Method” for any troublesome
    questions.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example of Bisection Method”**
    Links: University of South Florida:Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example of Bisection
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.1-TEXT2.pdf)”
    (PDF)  
        
     Instructions: Follow the example carefully.  Try to reproduce the
    calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**3.2 Newton-Raphson and Secant Methods** <span id="3.2"></span> 
**3.2.1 Newton-Raphson** <span id="3.2.1"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on the “Newton-Raphson Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on the “[Newton-Raphson
    Method](http://numericalmethods.eng.usf.edu/topics/newton_raphson.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” select the
    YouTube link after each title to view all of the video lectures. 
    There are 9 lectures total with an approximate run time of 65
    minutes.  How do you perform division by the Newton-Raphson
    method?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Newton-Raphson Method”**
    Link: University of South Florida:Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Newton-Raphson
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.2.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (15 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Newton-Raphson Method”**
    Links: University of South Florida:Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Newton-Raphson
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.2.1-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please attempt all questions on this multiple choice
    quiz.  If necessary, refer back to the “Textbook Chapter of
    Newton-Raphson Method” for any questions that pose difficulties. 
    You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.2.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example on Newton-Raphson
    Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example on Newton-Raphson
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.2.1-TEXT2.pdf)”
    (PDF)  
        
     Instructions: Please follow along with the example, and try to
    reproduce the calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**3.2.2 Secant Method** <span id="3.2.2"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Secant Method”**
    Links: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Secant
    Method](http://numericalmethods.eng.usf.edu/topics/secant_method.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” select the
    YouTube link to view all four videos: “Derivation of Secant Method:
    Approach 1 of 2,” “Derivation of Secant Method: Approach 2 of 2,”
    “Algorithm of Secant Method,” and “Example of Secant Method” (total
    run time: approximately 27 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Secant Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Secant
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.2.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (6 pages).  How does
    this method differ from the Newton-Raphson method?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Secant Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Secant
    Method](http://numericalmethods.eng.usf.edu/topics/secant_method.html)”
    (PDF, DOC, HTML, FLASH)  
        
     Instructions: Under “Multiple Choice Test,” select the appropriate
    format (PDF, DOC, HTML, or FLASH) to download the quiz.  Please
    attempt all questions on the multiple choice quiz.  If necessary,
    refer to “Textbook Chapter of Secant Method” for any questions that
    pose difficulties.  Please note that the solutions only appear in
    the Flash version.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example on Secant Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example on Secant
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-3.2.2-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow along with the example, and try to reproduce
    the calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**3.3 Nonlinear Equation Solving Exercise** <span id="3.3"></span> 
-   **Assessment: The Saylor Foundation’s “ME205: Unit 3.3 Exercise”**
    Link: The Saylor Foundation’s “[ME205: Unit 3.3
    Exercise](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/06/ME205-Subunit-3.3-Assignment-FINAL.pdf)”
    (PDF)  
        
     Instructions: Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 3.3
    Exercise Solution
    Guide](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/ME205-Subunit-3.3-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 2 hours to complete.


