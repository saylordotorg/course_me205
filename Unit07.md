**Unit 7: Numerical Integration** <span id="7"></span> 
**Integration may appear in a variety of numerical problems. For
example, in regression or optimization problems, one may wish to
minimize the integral of some measure of suboptimality or deviation. In
these applications, one often has data chosen by experiment or some
other constraint. At other times, one is free to choose where to sample
data for integration. These options, to some extent, determine the
algorithms available for numerical integration.*  
    
 *This unit reviews integral calculus, trapezoidal and quadratic
integration, Romberg integration, and Gaussian quadrature.**

**Unit 7 Time Advisory**  
This unit will take you approximately 11 hours to complete.  
  
 ☐    Subunit 7.1: 2 hours  
  
 ☐    Subunit 7.2: 2 hours  
  
 ☐    Subunit 7.3: 3 hours  
  
 ☐    Subunit 7.4: 4 hours

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Derive and apply the trapezoidal rule of integration.
-   Derive and apply Simpson’s rule of integration.
-   Distinguish Simpson’s method from the trapezoidal rule.
-   Estimate errors in trapezoidal and Simpson integration.
-   Derive and apply Romberg integration.
-   Derive and apply the Gauss quadrature method of integration.

**7.1 Review of Integral Calculus** <span id="7.1"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute: Autar Kaw’s Lecture “Accumulation Function”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute: Autar Kaw’s Lecture “[Accumulation
    Function](http://numericalmethods.eng.usf.edu/videos/youtube/07int/primer/primer_07int_accumulationexample.html)”
    (YouTube)  
        
     Instructions: View the entire video lecture (about 11 minutes).
     Can you come up with a concise definition of accumulation
    function?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Integral Calculus”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Integral
    Calculus](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.1-TEXT.pdf)”
    (PDF)  
        
     Instructions: Review the material in this chapter (24 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Background of Integral
    Calculus”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Background of Integral
    Calculus](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.1-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Complete the entire multiple choice quiz.  Refer to
    resources in subunit 7.1 for any questions that pose difficulty. 
    You can find the answers
    [here](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**7.2 Trapezoidal and Simpson Integration** <span id="7.2"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Trapezoidal Method”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Trapezoidal
    Method](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (24 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Simpson’s 1/3 Rule”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Simpson’s 1/3
    Rule](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.2-TEXT2.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (18 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Simpson’s 1/3 Rule”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Simpson’s 1/3
    Rule](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.2-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please complete the entire multiple choice quiz. 
    Refer to the resources in subunit 7.2 for any questions that pose
    difficulties.  You can find the answers
    [here](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.2-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s “Test Your Knowledge of Trapezoidal Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Trapezoidal
    Method](http://numericalmethods.eng.usf.edu/topics/trapezoidal_rule.html)”
    (PDF, DOC, HTML, FLASH)  
        
     Instructions: Under “Multiple Choice Test,” select the link for
    your preferred format (PDF, DOC, HTML, or FLASH) to download the
    quiz.  Please complete the entire multiple choice quiz.  Refer to
    the resources in subunit 7.2 for any questions that pose
    difficulties.  Please note that the solutions only appear in the
    Flash version of the quiz.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.3 Romberg Integration** <span id="7.3"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Romberg Integration”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Romberg
    Integration](http://numericalmethods.eng.usf.edu/topics/romberg_method.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” click on the
    YouTube link after each title to launch the videos.  Please view all
    6 videos in their entirety (approximately 55 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Romberg Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Romberg
    Method](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.3-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (12 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Romberg Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Romberg
    Method](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.3-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Complete the entire multiple choice quiz.  You can
    find the answers
    [here](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.3-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Chemical Engineering Example of Romberg Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Chemical Engineering Example of Romberg
    Method](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.3-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Read the entire example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**7.4 Gaussian Quadrature Rules** <span id="7.4"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Gauss Quadrature”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Gauss
    Quadrature](http://numericalmethods.eng.usf.edu/topics/gauss_quadrature.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” click on the
    YouTube link after the title of each video.  Please view all 7
    videos in their entirety (approximately 75 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Gauss Quadrature”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Gauss
    Quadrature](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.4-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (21 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Gauss Quadrature”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Gauss
    Quadrature](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.4-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all questions on the multiple choice quiz. 
    You can find the answers
    [here](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.4-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Chemical Engineering Example of Gauss Quadrature”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Computer Engineering Example of Gauss
    Quadrature](https://resources.saylor.org/archived/wp-content/uploads/2011/11/ME205-7.4-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the entire example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**7.5 An Exercise in Numerical Integration** <span id="7.5"></span> 
-   **Assessment: The Saylor Foundation’s “ME205: Unit 7.5 Exercise”**
    Link: The Saylor Foundation’s “[ME205: Unit 7.5
    Exercise](https://resources.saylor.org/archived/wp-content/uploads/2011/10/ME205-Subunit-7.5-Assignment-FINAL.pdf)”
    (PDF)  
        
     Instructions: Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 7.5
    Exercise Solution
    Guide](https://resources.saylor.org/archived/wp-content/uploads/2011/10/ME205-Subunit-7.5-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 3 hours to complete.


