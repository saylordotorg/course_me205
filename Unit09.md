---
layout: default
title: "ME205: Numerical Methods for Engineers"
course_description: "A review of the numeric methods most useful for engineers, with particular emphasis on numbers and binary systems, numerical differentiation, linear algebra, solving non-linear systems, regression and optimization, ordinary differential equations, and fourier and finite element methods."
next: ../Unit10
previous: ../Unit08
---
**Unit 9: Additional Tools** <span id="9"></span> 
**This unit is not meant to be an in-depth study on additional tools for
numerical methods in engineering.  Rather it is intended as an
inspiration for further study. The topics chosen for a cursory
introduction, Fourier transforms and finite element methods, find
widespread use in the dynamics of mechanical systems. Hence, some
acquaintance with the terminology and capabilities of the techniques and
concepts may serve you well in future study and/or applications.*  
    
 *This unit covers two topics which may at first seem unrelated (Fourier
transforms and finite element methods); through continued study you may
find links between these areas and many of the other topics covered in
this course. **

**Unit 9 Time Advisory**  
This unit will take you approximately 14 hours to complete.  
  
 ☐    Subunit 9.1: 9 hours  
  
         ☐    Sub-subunit 9.1.1: 3 hours  
  
         ☐    Sub-subunit  9.1.2: 6 hours  
    
                 ☐    Web Media: 3 hours  
  
                 ☐    Reading: 3 hours  
  
 ☐    Subunit 9.2:: 5 hours  
  
         ☐    Web Media: 2 hours  
  
         ☐    Reading: 3 hours

**Unit9 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Define Fourier series and the Fourier transform.
-   Find Fourier coefficients for a given data set or function and
    domain.
-   Describe the finite element method for one-dimensional problems.

**9.1 Fourier Series and the Fast Fourier Transform** <span
id="9.1"></span> 
**9.1.1 The Fourier Series** <span id="9.1.1"></span> 
-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.085: “Fourier Series (Part 1)” and “Fourier Series
    (Part 2)”**
    Links: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.085: “[Fourier Series (Part
    1)](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-28-fourier-series-part-1/)”
    (FLASH, MP4, or iTunes) and “[Fourier Series (Part
    2)](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-29-fourier-series-part-2/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=StnOg-q2tS8): Part 1  
     [YouTube](http://www.youtube.com/watch?v=9iJryWzLDIw&feature=relmfu):
    Part 2  
        
     Instructions: Please view these lectures before going on to the
    reading in this subunit.  Both videos are approximately 49 minutes.
     You may also access the transcript for the lectures by clicking on
    the “transcript” tab on each webpage and then the “Download this
    transcript-PDF” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: Chapter 4.1: “Fourier Series for Periodic Functions”**
    Link: MIT: Professor Gilbert Strang’s *Computational Science and
    Engineering:* Chapter 4.1:“[Fourier Series for Periodic
    Functions](http://math.mit.edu/cse/websections/)” (PDF)  
        
     Instructions: Go to the MIT website linked here, and click on the
    hyperlink titled “cse41.pdf.”  Please read this entire text (17
    pages).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**9.1.2 The Discrete Fourier Series** <span id="9.1.2"></span> 
-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.085: “Discrete Fourier Series”**
     Link: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.085: “[Discrete Fourier
    Series](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-30-discrete-fourier-series/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=bElQTlIWCr8)  
        
     Instructions: Please view the video lecture in its entirety
    (approximately 50 minutes). You may also access the transcript for
    the lectures by clicking on the “transcript” tab on each webpage and
    then the “Download this transcript-PDF” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of Maryland: Professor Ramani Duraiswami’s
    “Fast Fourier Transform”**
    Link: University of Maryland: Professor Ramani Duraiswami’s “[Fast
    Fourier
    Transform](http://www.umiacs.umd.edu/~ramani/cmsc828d_audio/)”
    (PDF)  
        
     Instructions: Scroll down the webpage linked here, and click on the
    hyperlink titled “Lecture 6” to download the PDF file.  Read this
    entire article (18 pages) and if interested, read the book chapter
    linked under “Lecture 6,” before proceeding to Professor Strang’s
    lectures on the Fourier Integral Transform and the Fast Fourier
    Transform in this subunit.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.085: “Filters, Fourier Integral Transform,” “Fourier
    Integral Transform (Part 2),” and “Fast Fourier Transform,
    Convolution”**
    Links: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.085: “[Filters, Fourier Integral
    Transform](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-33-filters-fourier-integral-transform/),”
    (FLASH, MP4, or iTunes) “[Fourier Integral Transform (Part
    2)](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-34-fourier-integral-transform-part-2/),”
    (FLASH, MP4, or iTunes) and “[Fast Fourier Transform,
    Convolution](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-31-fast-fourier-transform-convolution)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=aGnegoNe8Xo&feature=relmfu):
    Filters, Fourier Integral Transform  
     [YouTube](http://www.youtube.com/watch?v=Kv7eOsMVx6E): Fourier
    Integral Transform (Part 2)  
     [YouTube](http://www.youtube.com/watch?v=UdpdZ0diXUg): Fast Fourier
    Transform, Convolution  
        
     Instructions: Please view the first video lecture (“Filters,
    Fourier Integral Transform”) from 41:17 minutes to the end.  Then,
    view the entire “Fourier Integral Transform (Part 2)” video lecture
    (approximately 51 minutes).  Finally, view the “Fast Fourier
    Transform, Convolution” lecture up to 40:36 minutes.       
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: MIT Opencourseware: Professor Peter Shor’s Lecture Notes
    for Mathematics 18.310C: Principles of Applied Mathematics: “The
    Finite Fourier Transform” and “FFT”**
    Links: MIT Opencourseware: Professor Peter Shor’s Lecture Notes for
    Mathematics 18.310C: Principles of Applied Mathematics: “[The Finite
    Fourier
    Transform](http://ocw.mit.edu/courses/mathematics/18-310c-principles-of-applied-mathematics-fall-2007/lecture-notes/)”
    (PDF) and
    “[FFT](http://ocw.mit.edu/courses/mathematics/18-310c-principles-of-applied-mathematics-fall-2007/lecture-notes/)”
    (PDF)  
        
     Instructions: Go to the websites linked here, and click on the
    hyperlink “L23” for the first set of lecture notes and on the
    hyperlink “L24-FFT” for the second set.  Please read through
    Professor Shor’s notes to ensure that you understand and can
    reproduce the development and application of the FFT.        
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**9.2 Finite Element Methods (One-dimensional)** <span id="9.2"></span> 
-   **Reading: California State University, Fullerton: Professor John
    Mathew’s “Galerkin’s Method”**
    Link: California State University, Fullerton: Professor John
    Mathew’s “[Galerkin’s
    Method](http://math.fullerton.edu/mathews/n2003/GalerkinMod.html)”
    (HTML)  
        
     Instructions: Although these notes on Galerkin’s method are a bit
    advanced, it provides a good overview of the method.  Please read
    through these notes carefully, and re-read as necessary.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.085: “Finite Elements in 1D”**
    Link: MIT Opencourseware : Professor Gilbert Strang’s Mathematics
    18.085: “[Finite Elements in
    1D](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-17-finite-elements-in-1d-part-1/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=Vw4Gw9No008&feature=related)  
        
     Instructions: Please view the video lecture in its entirety (about
    54 minutes).  You may also access the transcript for the lectures by
    clicking on the “transcript” tab on each webpage and then the
    “Download this transcript-PDF” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Cornell University: Professor Nicholas Zabaras’s
    “Introduction to the FEM for Elliptic Problems”**
    Link: Cornell University: Professor Nicholas Zabaras’s
    [“Introduction to the FEM for Elliptic
    Problems”](http://mpdc.mae.cornell.edu/Courses/MAEFEM/MAEFEM.html#lectures)(PDF)  
        
     Instructions: Go to the Cornell website linked here, and click on
    the “PDF” hyperlink after the title “Introduction to the FEM for
    elliptic problems.”  Read these notes (60 pages).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: MIT Opencourseware: Professor Gilbert Strang’s
    Mathematics 18.085: “Finite Elements in 1D (Part 2)”**
    Link: MIT Opencourseware: Professor Gilbert Strang’s Mathematics
    18.085: “[Finite Elements in 1D (Part
    2)](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-18-finite-elements-in-1d-part-2/)”
    (FLASH, MP4, or iTunes)  
        
     Also available in:  
     [YouTube](http://www.youtube.com/watch?v=4B9aIlwEZcQ&feature=relmfu)  
        
     Instructions: Please view the entire video lecture (51:36 minutes)
    before moving on to the reading on the Galerkin Method in this
    subunit.  You may also access the transcript for the lectures by
    clicking on the “transcript” tab on each webpage and then the
    “Download this transcript-PDF” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


