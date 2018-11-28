Course Syllabus for "ME205: Numerical Methods for Engineers"
------------------------------------------------------------

**Please note: this [legacy course](https://sayloracademy.zendesk.com/hc/en-us/articles/206089967) does not offer a certificate and may contain 
broken links and outdated information.** Although archived, it is open 
for learning without registration or enrollment. Please consider contributing 
updates to [this course on GitHub](https://github.com/saylordotorg/course_me205) 
(you can also adopt, adapt, and distribute this course under the terms of 
the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/)). **To find fully-supported, current courses, [visit our 
Learn site](https://learn.saylor.org).**

Numerical methods have been used to solve mathematical expressions of
engineering and scientific problems for at least 4000 years (for some
historical discussion you may wish to browse the [Ethnomathematics
Digital Library](http://www.ethnomath.org/about.asp) or the [MacTutor
History of Mathematics
Archive](http://www-history.mcs.st-and.ac.uk/index.html) from St.
Andrews University).\*  Such methods apply numerical approximation in
order to convert continuous mathematical problems (for example,
determining the mechanical stress throughout a loaded truss) into
systems of discrete equations that can be solved with sufficient
accuracy by machine. Numerical methods provide a way for the engineer to
translate the language of mathematics and physics into information that
may be used to make engineering decisions. Often, this translation is
implemented so that calculations may be done by machines (computers).
The types of problems that you encounter as an engineer may involve a
wide variety of mathematical phenomena, and hence it will benefit you to
have an equally wide range of numerical methods with which to approach
some of these problems. This course will provide you with an
introduction to several of those numerical methods which you may then
find opportunity to practice later in the curriculum. Let us consider a
few examples in which numerical methods might offer a net benefit to the
engineer. 1. A new problem results in a numerical expression involving
logarithmic, polynomial, and trigonometric terms. Not only do you wish
to find the zeros of this particular expression, but you need to find
the zeros of 100,000 similar expressions per day.  Hence, you need an
automated procedure for doing such that can be implemented on a
computer. 2. Consider the manufacture of an oddly shaped part out of
very expensive materials. The manufacturing process involves cutting,
heating, cooling, and bending of the part. In order to optimize the
manufacturing process, you wish to understand the details of the
heating, cooling, and shaping processes. Modeling of these processes
requires consideration of transient heat flow in three dimensions and
transient deformation in three dimensions; further, the part is an
oddly-shaped domain. One approach to improve understanding of the
process is to numerically simulate the heating, cooling, and
deformation; this simulation involves the numerical solution of systems
of partial differential equations. 3. You have an empirical model of a
process that predicts temperature and oxygen content as a function of
time. The empirical model involves four parameters that need to be
estimated from measurements under a variety of conditions. There are
several nonlinear regression or optimization algorithms which might be
suitable for this task. As you progress through the curriculum, you will
encounter many more problems which might benefit from analysis by
numerical methods. Indeed, you may gain much insight by applying
numerical methods to a variety of problems that you encounter later in
the curriculum. This course will consist of ten units: an introduction
to the numerical properties of machine computations; numerical
differentiation; solution of non-linear equations; linear algebra (or
the solution of systems of linear equations); interpolation; regression
and optimization; numerical integration; numerical solution of ordinary
differential equations; numerical solution of partial differential
equations; and some miscellaneous numerical tools.  Each unit is
accompanied by lectures, readings, and exercises. \*Terms of Use: Please
respect the copyright and terms of use on the webpages above.

### Learning Outcomes

Upon successful completion of this course, the student will be able
to:  
  

-   Quantify absolute and relative errors.
-   Distinguish between round-off and truncation errors.
-   Interconvert binary and base-10 number representations.
-   Define and use floating-point representations.
-   Quantify how errors propagate through arithmetic operations.
-   Derive difference equations for first and second order derivatives.
-   Evaluate first and second order derivatives from numerical
    evaluations of continuous functions or table lookup of discrete
    data.
-   Describe situations in which numerical solutions to nonlinear
    equations are needed
-   Implement the bisection method for solving equations.
-   List advantages and disadvantages of the bisection method
-   Implement both Newton-Raphson and secant methods.
-   Describe the difference between Newton-Raphson and secant methods.
-   Demonstrate the relative performance of bisection, Newton-Raphson,
    and secant methods.
-   Define and identify special types of matrices.
-   Perform basic matrix operations.
-   Define and perform Gaussian elimination to solve a linear system.
-   Identify pitfalls of Gaussian elimination.
-   Define and perform Gauss-Seidel method for solving a linear system.
-   Use LU decomposition to find the inverse of a matrix.
-   Define and perform singular value decomposition; explain the
    significance of singular value decomposition.
-   Define interpolation.
-   Define and use direct interpolation to approximate data and find
    derivatives.
-   Define and use Newton’s divided difference method of interpolation.
-   Define and use Lagrange and spline interpolation.
-   Define regression.
-   Perform linear least-squares regression and nonlinear regression.
-   Derive and apply the trapezoidal rule and Simpson’s rule of
    integration.
-   Distinguish Simpson’s method from the trapezoidal rule.
-   Estimate errors in trapezoidal and Simpson integration.
-   Derive and apply Romberg and Gaussian quadrature for integration.
-   Define and distinguish between ordinary and partial differential
    equations.
-   Implement Euler’s methods for solving ordinary differential
    equations.
-   Investigate how step size affects accuracy in Euler’s method.
-   Implement and use the Runge-Kutta 2<sup>nd</sup> order method for
    solving ordinary differential equations.
-   Apply the shooting method to solve boundary-value problems.
-   Define Fourier series and the Fourier transform.
-   Find Fourier coefficients for a given data set or function and
    domain.
-   Describe the finite element method for one-dimensional problems.

### Course Requirements

In order to take this course, you must:  
  
 √    Have access to a computer.  
  
 √    Have frequent broadband Internet access.  
  
 √    Have the ability/permission to install plug-ins or software
(e.g. Adobe Reader or FLASH (see for solutions)).  
  
 √    Have the ability to download and save files and documents to
a computer.  
  
 √    Be able to download and install
[Scilab.\*](http://www.scilab.org)  
  
 √    Have the ability to open Microsoft files and documents (.doc,
.ppt, .xls, etc.).  
  
 √    Be competent in the English language.  
  
 √    Have read the [Saylor Student
Handbook](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/05/Saylor-StudentHandbook.pdf).   
  
 √    Have completed the following courses from “[The Core
Program](http://www.saylor.org/majors/mechanical-engineering/)” of the
Mechanical Engineering discipline:
[ME101](http://www.saylor.org/courses/me101/),
[ME102](http://www.saylor.org/courses/me102/),
[ME001/MA101](http://www.saylor.org/courses/me001/),
[ME002/MA102](http://www.saylor.org/courses/me002/), and
[ME003/MA221](http://www.saylor.org/courses/me003/).  
    
 \* Terms of Use: Please respect the copyright and terms of use for the
website above. 

### Course Information

Welcome to ME101.  Below, please find general information on this course
and its requirements.

**Course Designers: **Anonymous and Stephen Gibbs, Ph.D.

**Peer Reviewers:** Stephen Gibbs, Ph.D. 

**Primary Resources: ** This course is composed of a range of different
free, online materials. However, the course references the following
free, online resources from academic institutions that are key to
completing this course:

-   University of South Florida’s [Holistic Numerical Methods
    Institute](http://numericalmethods.eng.usf.edu/)
-   MIT Opencourseware: Professor Gilbert Strang’s [Linear
    Algebra](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/) Lectures

**Requirements for Completion:** In order to complete this course, you
will need to work through each unit and all of its assigned materials.
 Pay special attention to Unit 1, as this unit lays the groundwork for
understanding the more advanced, exploratory material presented in the
latter units. You will also need to complete:

-   Unit 1 Quizzes
-   Unit 2 Quizzes
-   Unit 3 Quizzes
-   Unit 4 Quizzes
-   Unit 5 Quizzes
-   Unit 6 Quizzes
-   Unit 7 Quizzes
-   Unit 8 Quizzes
-   Unit 9 Quizzes
-   Subunit 2.4 Assignment
-   Subunit 4.6 Assignment
-   Subunit 6.4 Assignment
-   Subunit 8.2 Assignment
-   The Final Exam

Each unit contains an assessment exercise and quizzes from the
University of South Florida’s Holistic Numerical Methods Institute. 
Please give time to these; they are the best way to test your knowledge
and learn.

Note that you will only receive an official grade on your Final Exam.
 However, in order to adequately prepare for this exam, you will need to
work through the unit multiple choice quizzes and assignments listed
above.

In order to “pass” this course, you will need to earn a 70% or higher on
the Final Exam. Your score on the exam will be tabulated as soon as you
complete it.  If you do not pass the exam, you may take it again.

**Time Commitment:** You should be able to complete this course in
approximately **128 hours** of study and creative effort.  Each unit
includes a “time advisory” that lists the amount of time you are
expected to spend on each subunit.  These should help you plan your time
accordingly.  It may be useful to take a look at these time advisories
and to determine how much time you have over the next few weeks to
complete each unit, and then to set goals for yourself. For example,
Unit 1 should take you 17 hours. Perhaps you can sit down with your
calendar and decide to complete subunit 1.1 (a total of 2 hours) on
Monday night; subunit 1.2 (a total of 3 hours) on Tuesday night; half of
subunit 1.4 (about 2 hours) on Wednesday night; the remainder of subunit
1.4 (about 2 hours) on Thursday night; etc.

**Tips/Suggestions: **Most of the materials for this course are easy to
read or study quickly; it is easy to convince yourself prematurely that
you understand the material. Re-reading may be a useful technique to
help better understand the material.  Most students learn this sort of
material best by implementing example calculations either by hand or by
machine. In fact, many students really begin to understand the
underlying mathematics only after implementing numerical calculations by
machine.

We encourage you to also take notes as you work through the course
materials.  These notes will be useful as you prepare for your Final
Exam. 

**Table of Contents:** You can find the course's units at the links below.

- [Unit 1](https://legacy.saylor.org/me205/Unit01/)
- [Unit 2](https://legacy.saylor.org/me205/Unit02/)
- [Unit 3](https://legacy.saylor.org/me205/Unit03/)
- [Unit 4](https://legacy.saylor.org/me205/Unit04/)
- [Unit 5](https://legacy.saylor.org/me205/Unit05/)
- [Unit 6](https://legacy.saylor.org/me205/Unit06/)
- [Unit 7](https://legacy.saylor.org/me205/Unit07/)
- [Unit 8](https://legacy.saylor.org/me205/Unit08/)
- [Unit 9](https://legacy.saylor.org/me205/Unit09/)
- [Unit 10](https://legacy.saylor.org/me205/Unit10/)
- [Final Exam](http://saylordotorg.github.io/LegacyExams/ME/ME205/ME205-FinalExam.html), [Answers](http://saylordotorg.github.io/LegacyExams/ME/ME205/ME205-FinalExam-Answers.html)
