**Unit 8: Numerical Solution of Ordinary Differential Equations** <span
id="8"></span> 
**Ordinary differential equations often appear in mechanical
engineering  through the study of dynamics amongst other areas. Often,
the equations do not permit easy solutions because of their form or the
variable coefficients.  In these cases, numerical solutions may be a
convenient way to tackle the problem.*  
    
 *This unit reviews some concepts of ordinary differential equations and
introduces the Euler’s method, the Runge-Kutta method, and the shooting
method (for boundary-value problems).**

**Unit 8 Time Advisory**  
This unit will take you approximately 13 hours to complete.  
  
 ☐    Subunit 8.1: 2 hours  
  
 ☐    Subunit 8.2: 6 hours  
      
         ☐    Web Media: 1.5 hours  
  
         ☐    Reading: 1.5 hours  
  
         ☐    Assessment: 3 hours  
  
 ☐    Subunit 8.3: 3 hours  
  
 ☐    Subunit 8.4: 2 hours

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Define and distinguish between ordinary and partial differential
    equations.
-   Implement Euler’s methods for solving ordinary differential
    equations.
-   Investigate how step size affects accuracy in Euler’s method.
-   Implement and use the Runge-Kutta 2<sup>nd</sup> order method for
    solving ordinary differential equations.
-    Apply the shooting method to solve boundary-value problems.

**8.1 Review of Ordinary Differential Equations** <span
id="8.1"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Ordinary Differential Equations”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Ordinary Differential
    Equations](http://numericalmethods.eng.usf.edu/topics/primer_ode.html)”
    (YouTube)  
        
     Instructions: View all 5 videos under the heading “Digital
    Audiovisual Lectures.”  To access each video, click on the YouTube
    link after the title.  The approximate run time is 41 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “A Primer on Ordinary Differential Equations”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s “[A Primer on Ordinary Differential
    Equations](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (39 pages).  What is
    the difference between an ordinary differential equation and a
    partial differential equation?  What constitutes initial and or
    boundary conditions?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**8.2 Euler’s Method** <span id="8.2"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on Euler’s Method**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s [Lectures on Euler’s
    Method](http://numericalmethods.eng.usf.edu/topics/euler_method.html)
    (YouTube)  
        
     Instructions: View all 4 videos under the heading “Digital
    Audiovisual Lectures:” “Euler’s Method of Solving ODEs: Derivation;”
    “Euler’s Method of Solving ODEs: Example;” “Euler’s Method of
    Estimating Integrals: Theory;” and “Euler’s Method of Estimating
    Integrals: Example.”  To access each video, click on the YouTube
    link after the video’s title.  The run time is approximately 37
    minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Euler’s Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Euler’s
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (12 pages).  Based on
    your reading about numerical differentiation, can you think of ways
    to improve Euler’s method?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Euler’s Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Euler’s
    Method](http://numericalmethods.eng.usf.edu/topics/euler_method.html)”
    (PDF, DOC, HTML, or FLASH)  
        
     Instructions: Under “Multiple Choice Test,” click on the link for
    your preferred format (PDF, DOC, HTML, or FLASH) to download the
    quiz.  Please complete the entire multiple choice quiz.  Please note
    that the solutions only appear in the Flash version.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Chemical Engineering Example of Euler’s Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Industrial Engineering Example of Euler’s
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.2-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Read the example in its entirety.  Try to reproduce
    the calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.086: “Finite Differences, Accuracy, Stability,
    Convergence” and Mathematics 18.085 “Exam Review”**
    Links: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.086: “[Finite Differences, Accuracy, Stability,
    Convergence](http://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-2-finite-differences-accuracy-stability-convergence/)”
    (FLASH, MP4, or iTunes) and Mathematics 18.085: “[Exam
    Review](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-14-exam-review/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=nlO9ci0kPLg): Finite
    Differences  
     [YouTube](http://www.youtube.com/watch?v=bciGyT6eeOE): Exam
    Review  
        
     Instructions: Please view the entire video lecture titled “Finite
    Differences, Accuracy, Stability, Convergence” (about 55 minutes). 
    Then, please view the entire “Exam Review” video (52:29 minutes). 
       
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation’s “ME205: Unit 8 Exercise
    Euler’s Method in Scilab”**
    Link: The Saylor Foundation’s “[ME205: Unit 8
    Exercise](http://www.saylor.org/site/wp-content/uploads/2011/10/ME205-Subunit-8.1-Assignment-FINAL1.pdf)”
    (PDF)  
        
     Instructions:  Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 8
    Exercise Solution
    Guide](http://www.saylor.org/site/wp-content/uploads/2011/10/ME205-Subunit-8.1-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 3 hours to complete.

**8.3 Runge-Kutta Methods** <span id="8.3"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Runge-Kutta 2nd Order Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s [Lectures on “Runge-Kutta 2nd Order
    Method](http://numericalmethods.eng.usf.edu/topics/runge_kutta_2nd_method.html)”
    (YouTube)  
        
     Instructions: Please view all 8 videos under the heading “Digital
    Audiovisual Lectures” in their entirety (run time: about 75
    minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Runge-Kutta 2nd Order Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Runge-Kutta 2nd Order
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.3-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (17 pages).  Based on
    your reading about numerical differentiation, can you think of ways
    to improve Runge-Kutta 2nd Order Method?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Runge-Kutta 2nd Order
    Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Runge-Kutta 2nd Order
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.3-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all of the questions on the multiple choice
    quiz.  You can find the answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.3-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Industrial Engineering Example of Runge-Kutta 2nd Order
    Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Industrial Engineering Example of Runge-Kutta 2nd
    Order
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.3-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Read through the entire example, and try to reproduce
    the calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**8.4 Shooting Method** <span id="8.4"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Shooting Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s [Lectures on “Shooting
    Method](http://numericalmethods.eng.usf.edu/topics/shooting_method.html)”
    (YouTube)  
        
     Instructions: View all 6 videos under the heading “Digital
    Audiovisual Lectures” in their entirety (about 35 minutes).  To
    access each video, click on the YouTube link following the video’s
    title.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Shooting Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Shooting
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.4-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (11 pages).  Based on
    your reading about numerical differentiation, can you think of ways
    to improve Shooting Method?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Shooting Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Shooting
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.4-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please complete the entire assessment.  You can find
    the answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-8.4-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).


