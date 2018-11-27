---
layout: default
title: "ME205: Numerical Methods for Engineers"
course_description: "A review of the numeric methods most useful for engineers, with particular emphasis on numbers and binary systems, numerical differentiation, linear algebra, solving non-linear systems, regression and optimization, ordinary differential equations, and fourier and finite element methods."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Numerical Differentiation** <span id="2"></span> 
**If you have experience with the definition of a derivative, then this
unit may seem rather trivial. There are, however, several ways with
which to approximate the value of the derivative of a function or set of
discrete data. The details of the bookkeeping involved in computing such
approximations can be very important in the use of those approximations
in more advanced numerical algorithms. Hence, it is worthwhile to spend
a little time understanding the details of the bookkeeping involved. **

**Unit 2 Time Advisory**  
Time Advisory:  This unit will take you approximately 13 hours to
complete.  
  
 ☐    Subunit 2.1: 2 hours  
  
 ☐    Subunit 2.2: 4 hours  
  
         ☐    Web Media: 1 hour  
  
         ☐    Reading: 2 hours  
  
         ☐    Assessment: 1 hour  
  
 ☐    Subunit 2.3: 4 hours  
  
         ☐    Web Media: 1 hour  
  
         ☐    Reading: 2 hours  
  
         ☐    Assessment: 1 hour  
  
 ☐    Subunit 2.4: 3 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Derive difference equations for first and second order derivatives.
-   Evaluate first and second order derivatives from numerical
    evaluations of continuous functions or table lookup of discrete
    data.

**2.1 Review of Differentiation** <span id="2.1"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Differential Calculus”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Differential
    Calculus](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the chapter in its entirety (32 pages). 
    You may skim through the chapter if it is a review for you.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute: Autar Kaw’s “Background of Differentiation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute: Autar Kaw’s “[Background of
    Differentiation](http://numericalmethods.eng.usf.edu/videos/youtube/02dif/background/background_02dif_introduction.html)”
    (YouTube)  
      
     Instructions: Please view the entire 7-minute video.  Please note
    that the material in this subunit may be a review.  Make sure to
    test your knowledge by completing the multiple choice quiz before
    skipping this section.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Background of
    Differential Calculus”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Background of Differential
    Calculus](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.1-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all questions in the multiple choice quiz.
     If you are having difficulty answering any of the questions, make
    sure to refer back to and review the resources in subunit 2.1.  You
    can find the answers
    [here](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**2.2 Differentiation of Continuous Functions** <span id="2.2"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Numerical Differentiation of
    Continuous Functions”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Numerical Differentiation of
    Continuous
    Functions](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Read the entire chapter (18 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Differentiation of Continuous Functions”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Differentiation of Continuous
    Functions](http://numericalmethods.eng.usf.edu/topics/continuous_02dif.html)”
    (YouTube)  
        
     Instructions: Please view all 9 videos under the heading “Digital
    Audiovisual Lectures.”  You may access each video by clicking on the
    YouTube link after each title.  The total run time is approximately
    63 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Numerical
    Differentiation of Continuous Functions”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Background of Numerical
    Differentiation of Continuous
    Functions](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.2-ASSESSMENT2.pdf)”
    (PDF)  
      
     Instructions: Complete all questions in the multiple choice quiz.
     If you encounter any difficulties in answering a question, refer to
    the resources in subunit 2.2.  You can find the answers
    [here](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.2-ASSESSMENT2ANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**2.3 Differentiation of Discrete Data** <span id="2.3"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Numerical Differentiation of
    Discrete Functions”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Numerical Differentiation of
    Discrete
    Functions](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-2.3-TEXT.pdf)”
    (PDF)  
        
     Instructions: Read the entire chapter (9 pages).  How does the
    treatment differ for discrete data and continuous functions?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s “Differentiation of Discrete Functions” Lectures**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Differentiation of Discrete
    Functions](http://numericalmethods.eng.usf.edu/topics/discrete_02dif.html)”
    (YouTube)  
        
     Instructions: Under the “Digital Audiovisual Lectures” heading,
    select the YouTube links for each video.  View all four videos in
    their entirety: “Divided Difference Approach,” “Polynomial
    Interpolation Method,” “Newton’s Divided Difference Polynomial
    Method: Theory,” and “Newton’s Divided Difference Polynomial Method:
    Example.”  The total run time is approximately 35 minutes.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Numerical
    Differentiation of Discrete Functions”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Background of Numerical
    Differentiation of Discrete
    Functions](https://resources.saylor.org/archived/wp-content/uploads/2013/06/ME205-2.3-TestYourKnowledgeofNumericalDifferentiationofDiscreteFunctions.pdf)”
    (PDF)  
        
     Instructions: Attempt all questions in the multiple choice quiz. 
    If you encounter any difficulties answering a question, please refer
    to the resources in subunit 2.3.  You can find the answers
    [here](http://mathforcollege.com/nm/mcquizzes/02dif/quiz_02dif_discrete_solution.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**2.4 An Exercise in Numerical Differentiation** <span id="2.4"></span> 
-   **Assessment: The Saylor Foundation’s “ME205: Unit 2.4 Exercise”**
    Link: The Saylor Foundation’s “[ME205: Unit 2.4
    Exercise](https://resources.saylor.org/archived/wp-content/uploads/2012/07/ME205-Subunit-2.4-Assignment-FINAL.pdf)”
    (PDF)  
        
     Instructions: Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 2.4
    Exercise Solution
    Guide](https://resources.saylor.org/archived/wp-content/uploads/2012/07/ME205-Subunit-2.4-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 3 hours to complete.


