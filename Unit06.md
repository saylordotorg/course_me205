**Unit 6: Regression and Optimization** <span id="6"></span> 
**Regression and optimization are related ideas. Both have to do with
finding the best solution to a quantifiable problem subject to certain
constraints. For example, you have probably engaged in the exercise of
drawing a “best-fit” line through three or more points by eye. In most
cases, the line cannot pass directly through all of the points; rather
we must make some judgments about which points are important and what
deviations are important. This “best-fit” line then permits us to infer
two parameters which describe the line; these could be a slope and
intercept. If we have several more than three data points, then we may
employ more complex models than just lines.**

**Unit 6 Time Advisory**  
This unit will take you approximately 15 hours to complete.  
  
 ☐    Subunit 6.1: 2 hours  
  
 ☐    Subunit 6.2: 4 hours  
  
 ☐    Subunit 6.3: 6 hours  
    
         ☐    Web Media: 2.5 hours  
  
         ☐    Reading: 2.5 hours  
  
         ☐    Assessment: 1 hour  
  
 ☐    Subunit 6.4: 3 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Define regression.
-   Perform linear least-squares regression.
-   Perform nonlinear regression.

**6.1 Introduction to Regression** <span id="6.1"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “A Primer on Statistical Terminology for Regression
    Analysis” and “Introduction to Regression”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[A Primer on Statistical Terminology for Regression
    Analysis](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.1-TEXT1.pdf)”
    (PDF) and “[Introduction to
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.1-TEXT2.pdf)”
    (PDF)  
        
     Instructions: Please read both chapters in their entirety (15
    pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge on Background of
    Regression”**
    Link:University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge on Background of
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.1-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all questions in the multiple choice quiz. 
    You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**6.2 Linear Regression** <span id="6.2"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Linear Regression”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s "[Lectures on “Linear
    Regression](http://numericalmethods.eng.usf.edu/topics/linear_regression.html)”
    (YouTube)  
        
     Instructions: Under the “Digital Audiovisual Lectures” heading,
    click on the YouTube link after each title to launch each video. 
    Please watch all 7 videos in their entirety (approximately 55
    minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Linear Regression”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Linear
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (21 pages).  Based on
    your reading about numerical differentiation, can you think of ways
    to improve or tailor linear regression?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Linear Regression”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Linear
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.2-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all questions on the multiple choice quiz. 
    You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.2-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Industrial Engineering Example of Linear Regression”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Industrial Engineering Example of Linear
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.2-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**6.3 Nonlinear Regression** <span id="6.3"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Nonlinear Regression”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s [Lectures on “Nonlinear
    Regression](http://numericalmethods.eng.usf.edu/topics/nonlinear_regression.html)”
    (YouTube)  
        
     Instructions: Under the “Digital Audiovisual Lectures” heading,
    click on the YouTube link after each title to launch each video.
     Please watch all 20 videos in their entirety (about 2.5 hours).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Nonlinear Regression”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Nonlinear
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.3-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (32 pages).  Based on
    your reading about numerical differentiation, can you think of ways
    to improve Nonlinear Regression?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Nonlinear Regression”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Nonlinear
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.3-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all of the questions on the multiple choice
    quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.3-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Electrical Engineering Example of Nonlinear
    Regression”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Electrical Engineering Example of Nonlinear
    Regression](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-6.3-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**6.4 A Brief Exercise in Regression** <span id="6.4"></span> 
-   **Assessment: The Saylor Foundation’s “ME205: Unit 6.4 Exercise”**
    Link: The Saylor Foundation’s “[ME205: Unit 6.4
    Exercise](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/ME205-Subunit-6.4-Assignment-FINAL.pdf)”
    (PDF)  
        
     Instructions: Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 6.4
    Exercise Solution
    Guide](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/ME205-Subunit-6.4-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 3 hours to complete.


