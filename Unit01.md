---
layout: default
title: "ME205: Numerical Methods for Engineers"
course_description: "A review of the numeric methods most useful for engineers, with particular emphasis on numbers and binary systems, numerical differentiation, linear algebra, solving non-linear systems, regression and optimization, ordinary differential equations, and fourier and finite element methods."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Introduction to Machine-Based Numerical Computations** <span
id="1"></span> 
**This unit deals with the way numbers are represented by machine and
the implications of that representation for numerical algorithms. As a
simple example, consider the precision with which the difference between
two numbers represented as 0.10437 and 0.10416 can be determined. If the
numerical algorithm is sensitive to such limited precision, then it may
not take many additional operations for the limited precision to cause
problems.*  
    
 *This unit covers quantifying errors or precision, sources of those
errors or limited precision, representation of numbers by the binary
system on machines, the representation of floating point or decimal
numbers, and the propagation of errors through an algorithm. Each
subunit is accompanied by a short quiz to help you review.**

**Unit 1 Time Advisory**  
Time Advisory: This unit will take you approximately 17 hours to
complete.  
  
 ☐    Subunit 1.1: 2 hours  
  
 ☐    Subunit 1.2: 3 hours  
  
 ☐    Subunit 1.3: 4 hours  
  
         ☐    Web Media: 1 hour  
  
         ☐    Reading: 2 hours  
  
         ☐    Assessment: 1 hour  
  
 ☐    Subunit 1.4: 4 hours  
  
         ☐    Web Media: 1 hour  
  
         ☐    Reading: 2 hours  
  
         ☐    Assessment: 1 hour  
  
 ☐    Subunit 1.5: 4 hours  
  
         ☐    Web Media: 1 hour  
  
         ☐    Reading: 2 hours  
  
         ☐    Assessment: 1 hour

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Quantify absolute and relative errors.
-   Distinguish between round-off and truncation errors.
-   Interconvert binary and base-10 number representations.
-   Define and use floating-point representations.
-   Quantify how errors propagate through arithmetic operations.

**1.1 Preliminaries** <span id="1.1"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Introduction to Numerical
    Methods”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Introduction to Numerical
    Methods](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (8 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Introduction to
    Numerical Methods”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s [“Test Your Knowledge of Introduction to Numerical
    Methods”](http://school.saylor.org/mod/quiz/view.php?id=1780) (HTML)  
        
     Instructions: Complete this multiple choice quiz.  
        
     Terms of Use: The assessment above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/).

**1.2 Numerical Errors** <span id="1.2"></span> 
**1.2.1 Measuring Errors** <span id="1.2.1"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Measuring Errors”**

    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Measuring
    Errors](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.2.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (10 pages).   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Introduction to
    Measuring Errors”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s [“Test Your Knowledge of Introduction of Measuring
    Errors”](http://school.saylor.org/mod/quiz/view.php?id=1797)
    (HTML)  
        
     Instructions: Complete all questions on the multiple choice quiz.  
      
     Completing this assessment should approximately take 30 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/).

**1.2.2 Sources of Error** <span id="1.2.2"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Sources of Error”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Sources of
    Error”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.2.2-TEXT.pdf)(PDF)  
        
     Instructions: Please read the entire chapter (8 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Sources of Error”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Sources of
    Error](http://numericalmethods.eng.usf.edu/topics/sources_of_error.html)”
    (YouTube)  
      
      
     Instructions: Under “Digital Audiovisual Lectures,” click on the
    links to YouTube for all 6 lectures: “Round-Off Error: Definition
    and Examples,” “Effect of Carrying Significant Digits,” “Truncation
    Error: Definition,” “Truncation Error: Example: Series,” “Truncation
    Error: Example: Integration,” and “Truncation Error: Example:
    Differentiation” (run time: approximately 42 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Introduction to Sources
    of Error”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Introduction of Sources of
    Error](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.2.2-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please attempt all the questions on this multiple
    choice quiz.  You can find the
    answers [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.2.2-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**1.3 Binary System** <span id="1.3"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Binary Representation of Numbers”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Binary Representation of
    Numbers](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.3-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (12 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Binary Representation of Numbers”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Binary Representation of
    Numbers](http://numericalmethods.eng.usf.edu/topics/binary_representation.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” select the
    YouTube links for the following lectures: “Introduction to Binary
    Representation,” “Base-10 to Base-2 Conversion Method,” and “Base-10
    to Base-2 Conversion another Method” (run time: approximately 25
    minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Introduction to Binary
    Representation of Numbers”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Introduction of Binary
    Representation of
    Numbers](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.3-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please attempt all of the questions on this multiple
    choice quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.3-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**1.4 Floating Point Numbers** <span id="1.4"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Floating Point Representation of
    Numbers”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Floating Point Representation of
    Numbers](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.4-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (12 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Floating Point Representation of Numbers”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Floating Point Representation of
    Numbers](http://numericalmethods.eng.usf.edu/topics/floatingpoint_representation.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” please select
    the links to YouTube and view all 8 video lectures.  The total run
    time is approximately 57 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Introduction to Floating
    Point Representation of Numbers”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Introduction of Floating Point
    Representation of
    Numbers](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.4-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please attempt all of the questions on this multiple
    choice quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.4-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**1.5 Error Propagation** <span id="1.5"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Propagation of Errors”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Propagation of
    Errors](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-1.5-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (4 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s “Test Your Knowledge of Introduction to Propagation of
    Errors”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Introduction of Propagation of
    Errors](http://numericalmethods.eng.usf.edu/topics/propagation_of_errors.html)”
    (PDF, DOC, HTML, FLASH)  
        
     Instructions: Under the “Multiple Choice Test” heading, please
    select your preferred format (PDF, DOC, HTML, or FLASH) to download
    the quiz.  Please attempt all of the questions on this multiple
    choice quiz.  Note that the solutions appear only in the Flash
    version.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


