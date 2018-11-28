---
layout: default
title: "ME205: Numerical Methods for Engineers"
course_description: "A review of the numeric methods most useful for engineers, with particular emphasis on numbers and binary systems, numerical differentiation, linear algebra, solving non-linear systems, regression and optimization, ordinary differential equations, and fourier and finite element methods."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: Applications of Numerical Methods in Linear Algebra** <span
id="4"></span> 
**A witticism common among practitioners of mathematics is that a
mathematical problem, to be solvable, must at some point be mapped onto
a problem in linear algebra.  While not reflecting the entire truth,
this viewpoint is sufficiently correct that, in this course, numerical
methods and their application to engineering problems may often be
understood in terms of fundamental problems in linear algebra.*  
    
 *This unit will focus on a few of those fundamental problems. After
providing a review of some basic properties of matrices, matrix algebra,
and their relationship to linear algebra, the unit then covers
introductions to  solving systems of linear equations by elimination and
iterative methods, techniques for finding the inverse of a matrix, and
the concept of singular value decomposition for non-square matrices.* *

**Unit 4 Time Advisory**  
Time Advisory: This unit will take you approximately 18 hours to
complete.  
  
 ☐    Subunit 4.1: 3 hours  
  
 ☐    Subunit 4.2: 3 hours  
  
 ☐    Subunit 4.3: 3 hours  
  
 ☐    Subunit 4.4: 3 hours  
  
 ☐    Subunit 4.5: 3 hours  
  
 ☐    Subunit 4.6: 3 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Define and identify special types of matrices.
-   Perform basic matrix operations.
-   Define and perform Gaussian elimination to solve a linear system.
-   Identify pitfalls of Gaussian elimination.
-   Define and perform Gauss-Seidel method for solving a linear system.
-   Use LU decomposition to find the inverse of a matrix.
-   Define and perform singular value decomposition; explain the
    significance of singular value decomposition.

**4.1 Overview of Linear Algebra** <span id="4.1"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapters on Matrix Algebra”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Textbook Chapters on Matrix Algebra:
    [Introduction](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-TEXT1.pdf)
    (PDF),
    [Vectors](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-TEXT2.pdf)
    (PDF), [Binary Matrix
    Operations](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-TEXT3.pdf)
    (PDF), [Unary Matrix
    Operations](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-TEXT4.pdf)
    (PDF), and [Systems of
    Equations](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-TEXT5.pdf)
    (PDF)  
        
     Instructions: Please read all five textbook chapters (Introduction,
    Vectors, Binary Matrix Operations, Unary Matrix Operations, and
    Systems of Equations) in their entirety.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: Stanford University: Professor Stephen Boyd’s “A Primer
    on Matrices”**

    Link: Stanford University: Professor Stephen Boyd’s “[A Primer on
    Matrices](http://see.stanford.edu/materials/lsoeldsee263/Additional1-notes-matrix-primer.pdf)”
    (PDF)  
        
     Instructions: Please read and work through the examples before
    watching Professor Strang’s lecture on Key Ideas of Linear Algebra
    in this subunit.     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.085: “Recitation 1: Key Ideas of Linear Algebra”**
    Link: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.085: “[Recitation 1: Key Ideas of Linear
    Algebra](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/recitation-1-key-ideas-of-linear-algebra/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=0oBJN8F616U&feature=relmfu)  
        
     Instructions: Please view the video lecture in its entirety (49:31
    minutes).  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above found at [this
    link](http://ocw.mit.edu/terms/).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Background of
    Simultaneous Linear Equations”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Introduction of Background of
    Simultaneous Linear
    Equations](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-ASSESSMENT.pdf)”
    (PDF)  
      
     Instructions: Please attempt all questions for this multiple choice
    quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**4.2 Gaussian Elimination** <span id="4.2"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Gaussian Elimination”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s "[Lectures on “Gaussian
    Elimination](http://numericalmethods.eng.usf.edu/topics/gaussian_elimination.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” please select
    the YouTube link after the title of each lecture.  View all 17
    lectures on Gaussian Elimination in their entirety (approximately
    2.25 hours).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Gaussian Elimination”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Gaussian
    Elimination](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Read the entire chapter (27 pages).  Based on your
    reading about numerical differentiation, can you think of ways to
    improve Gaussian Elimination?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s Test Your Knowledge of Gaussian Elimination”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Gaussian
    Elimination](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.2-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please attempt all questions on this multiple choice
    quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.2-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example of Gaussian
    Elimination”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example of Gaussian
    Elimination](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.2-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the entire example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**4.3 Gauss-Seidel Method** <span id="4.3"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Gauss-Seidel Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s "[Lectures on “Gauss-Seidel
    Method](http://numericalmethods.eng.usf.edu/topics/gauss_seidel.html)”
    (YouTube)  
        
     Instructions: Please view the six video lectures in their
    entirety.  To access the lectures, select the YouTube link after
    each title under the heading “Digital Audiovisual Lectures.”  The
    total run time is approximately is 38 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on Gauss-Seidel Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on Gauss-Seidel
    Method”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.3-TEXT.pdf) (PDF)  
        
     Instructions: Read the entire chapter (15 pages).  Based on your
    reading about numerical differentiation, can you think of ways to
    improve Gauss-Seidel method?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of Gauss-Seidel Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of Gauss-Seidel
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.3-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please attempt all questions on the multiple choice
    quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.3-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example of Gauss-Seidel
    Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example of Gauss-Seidel
    Method](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.3-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Read through the example in its entirety, and try to
    reproduce the calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**4.4 LU Decomposition** <span id="4.4"></span> 
-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “LU Decomposition”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[LU
    Decomposition](http://numericalmethods.eng.usf.edu/topics/lu_decomposition.html)”
    (YouTube)  
        
     Instructions: View the 8 video lectures under the heading “Digital
    Audiovisual Lectures.”  To access the videos, click on the YouTube
    link after each video’s title.  The total run time is approximately
    48 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter on LU Decomposition”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter on LU
    Decomposition](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.4-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (16 pages).  Based on
    your reading about numerical differentiation, can you think of ways
    to improve LU Decomposition?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of LU Decomposition”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of LU
    Decomposition](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.4-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Work through each question on the multiple choice
    quiz.  You can find the answers
    [here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.4-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Chemical Engineering Example of LU Decomposition”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Chemical Engineering Example of LU
    Decomposition](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/11/ME205-4.4-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the entire example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.06: “Factorization into A = LU”**
     Link: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.06: “[Factorization into A =
    LU](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-4-factorization-into-a-lu/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=5hO3MrzPa0A)  
        
     Instructions: Please view the entire lecture (50:13 minutes) before
    moving on to the reading in this subunit.  You may also access the
    transcript of the video by clicking on the “transcript” tab and then
    the “download this transcript” link on the webpage.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed at [this link](http://ocw.mit.edu/terms/).

**4.5 Singular Value Decomposition** <span id="4.5"></span> 
-   **Web Media: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.06: “Singular Value Decomposition”**
    Link: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.06: “[Singular Value
    Decomposition](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-29-singular-value-decomposition/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=Nx0lRBaXoz4)  
        
     Instructions: Please view the entire lecture (41:34 minutes) before
    moving on to the reading in this subunit.  You may also access the
    transcript of the video by clicking on the “transcript” tab and then
    the “download this transcript” link on the webpage.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed at [this link](http://ocw.mit.edu/terms/).

-   **Reading: University of Puget Sound: Professor Robert Beezer’s
    “Section SVD Singular Value Decomposition”**
    Link: University of Puget Sound: Professor Robert Beezer’s “[Section
    SVD Singular Value
    Decomposition](http://linear.ups.edu/jsmath/latest/fcla-jsmath-latestli107.html#x108-451000)”
    (HTML)  
        
     Instructions: After viewing Professor Strang’s lecture for this
    subunit, please read this section in its entirety to reinforce and
    clarify the terminology and main ideas presented in the lecture. 
    Refer back to the lecture, if necessary.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed at [this link](http://www.gnu.org/licenses/fdl.html).

**4.6 An Exercise in Singular Value Decomposition** <span
id="4.6"></span> 
-   **Assessment: The Saylor Foundation’s “ME205: Unit 4.6 Exercise”**
    Link: The Saylor Foundation’s “[ME205: Unit 4.6
    Exercise](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/ME205-Subunit-4.6-Assignment-FINAL.pdf)”
    (PDF)  
        
     Instructions: Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 4.6
    Exercise Solution
    Guide](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/ME205-Subunit-4.6-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 3 hours to complete.


