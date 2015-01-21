**Unit 5: Interpolation** <span id="5"></span> 
**Interpolation is the process of inferring the value of a discretely
sampled function at a value(s) of the independent variable(s) that is
within the domain of sampled values. Several schemes have been used for
interpolation, but most rely upon polynomial fitting.*  
    
 *In engineering practice, interpolation is useful for interpreting
experiment or process observations, making the best use of data, and
predicting outcomes for underexplored conditions.*  
    
 *You may find the material in this unit repetitive; it is, but the
repetition provides different historical and utilitarian perspectives on
the process of interpolation. **

**Unit 5 Time Advisory**  
This unit will take you approximately 14 hours to complete.  
  
 ☐    Subunit 5.1: 2 hours  
  
 ☐    Subunit 5.2: 3 hours  
  
 ☐    Subunit 5.3: 3 hours  
  
 ☐    Subunit 5.4: 3 hours  
  
 ☐    Subunit 5.5: 3 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Define interpolation.
-   Define and use direct interpolation to approximate data and find
    derivatives.
-   Define and use Newton’s divided difference method of interpolation.
-   Define and use Lagrange interpolation.
-   Define and use spline interpolation.

**5.1 Introduction to Interpolation** <span id="5.1"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter Definition of Interpolation” and
    “Textbook Chapter History of Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s [“Textbook Chapter Definition of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.1-TEXT1.pdf)”
    (PDF) and “[Textbook Chapter History of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.1-TEXT2.pdf)”
    (PDF)  
        
     Instructions: Please read both chapters in their entirety (4 pages
    total).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Polynomial Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Polynomial
    Interpolation](http://numericalmethods.eng.usf.edu/topics/primer_interpolation.html)”
    (YouTube)  
      
     Instructions: Under the “Digital Audiovisual Lectures” heading,
    click on the YouTube links to watch both videos: “Uniqueness of
    Polynomial Interpolant: Part 1 of 2” and “Uniqueness of Polynomial
    Interpolant: Part 2 of 2” (run time: approximately 18 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge on Background of
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge on Background of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.1-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Attempt all of the questions on the multiple choice
    exam.  You can find the answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.1-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**5.2 Direct Method of Interpolation** <span id="5.2"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of the Direct Method of
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of the Direct Method of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.2-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (12 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Direct Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Direct
    Interpolation](http://numericalmethods.eng.usf.edu/topics/direct_method.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” select the
    YouTube link after each title to launch the video.  Watch all four
    videos (about 35 minutes): “Linear Interpolation;” “Quadratic
    Interpolation;” “Cubic Interpolation: Part 1 of 2;” and “Cubic
    Interpolation: Part 2 of 2.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of the Direct Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of the Direct
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.2-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please work through each question on the multiple
    choice quiz. You can find the answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.2-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Industrial Engineering Example on Direct Method of
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Industrial Engineering Example on Direct Method of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.2-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the example, and try to reproduce the
    calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**5.3 Newton’s Divided Difference Method** <span id="5.3"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of the Newton’s Divided Difference
    Method of Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of the Newton’s Divided Difference
    Method of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.3-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (17 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Newton’s Divided Difference
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Newton’s Divided Difference
    Interpolation](http://numericalmethods.eng.usf.edu/topics/newton_divided_difference_method.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” click on the
    YouTube link after each lecture title to launch the video.  Please
    view all 9 videos in their entirety (approximately 69 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge of the Newton’s Divided
    Difference Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of the Newton’s Divided Difference
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.3-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please complete the entire multiple choice quiz.  You
    can find the answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.3-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Industrial Engineering Example on Newton’s Divided
    Difference Method of Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Civil Engineering Example on Newton’s Divided
    Difference Method of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.3-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**5.4 Lagrangian Interpolation** <span id="5.4"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Lagrange Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Lagrange
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.4-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (15 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Lagrange Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Lagrange
    Interpolation](http://numericalmethods.eng.usf.edu/topics/lagrange_method.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” click on the
    YouTube link after each title to launch a video.  Please watch all 6
    videos in their entirety (about 47 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge on Background of
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Test Your Knowledge of the Lagrange
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.4-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Complete the multiple choice quiz.  You can find the
    answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.4-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example on Lagrange Method of
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example on Lagrange Method of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.4-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the example, and try to reproduce the
    calculations.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**5.5 Spline Interpolation** <span id="5.5"></span> 
-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Textbook Chapter of Spline Method”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s “[Textbook Chapter of Spline
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.5-TEXT.pdf)”
    (PDF)  
        
     Instructions: Please read the entire chapter (17 pages).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Web Media: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “Spline Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s Lectures on “[Spline
    Interpolation](http://numericalmethods.eng.usf.edu/topics/spline_method.html)”
    (YouTube)  
        
     Instructions: Under “Digital Audiovisual Lectures,” click on the
    YouTube link after each title to access the videos.  Please watch
    all 6 videos in their entirety (about 47 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of South Florida: Holistic Numerical
    Methods Institute’s “Test Your Knowledge on Background of
    Interpolation”**
    Link: University of South Florida: Holistic Numerical Methods
    Institute’s [Test Your Knowledge of the Spline
    Method](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.5-ASSESSMENT.pdf)”
    (PDF)  
        
     Instructions: Please complete the entire multiple choice quiz. You
    can find the answers
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.5-ASSESSMENTANSWERS.pdf)
    (PDF).  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

-   **Reading: University of South Florida: Holistic Numerical Methods
    Institute’s “Mechanical Engineering Example on Spline Method of
    Interpolation”**
    Link: University of South Florida:  Holistic Numerical Methods
    Institute’s “[Mechanical Engineering Example on Spline Method of
    Interpolation](http://www.saylor.org/site/wp-content/uploads/2011/11/ME205-5.5-TEXT2EXAMPLE.pdf)”
    (PDF)  
        
     Instructions: Follow the example, and try to reproduce the
    calculations as you read.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the University of South Florida and the original
    version can be found [here](http://numericalmethods.eng.usf.edu/)
    (HTML).

**5.6 An Exercise in Interpolation** <span id="5.6"></span> 
-   **Assessment: The Saylor Foundation’s “ME205: Unit 5.6 Exercise”**
    Link: The Saylor Foundation’s “[ME205: Unit 5.6
    Exercise](http://www.saylor.org/site/wp-content/uploads/2011/10/ME205-Subunit-5.6-Assignment-FINAL.pdf)”
    (PDF)  
        
     Instructions: Please perform this exercise.  When you are done,
    check your work against The Saylor Foundation’s “[ME304: Unit 5.6
    Exercise Solution
    Guide](http://www.saylor.org/site/wp-content/uploads/2011/10/ME205-Subunit-5.6-Answer-Key-FINAL.pdf)"
    (PDF).  This exercise should require less than 2 hours to complete.


