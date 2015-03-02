---
layout: default
title: "MA241: Real Analysis I"
course_description: "A detailed introduction to the rigorous examination of the real number system and the foundations of calculus."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Metric Spaces** <span id="2"></span> 
*In this unit, we will learn about various topological notions and will
be introduced to the more abstract notion of a metric space. A metric is
a function which takes two points in a certain set and tells how “far
apart” they are and which satisfies three special requirements. The
metric can be used to define many different properties of the set to
which it applies (the* metric space*). All of the concepts which you
learned in calculus, especially limits, can be understood and extended
in the context of metric spaces.*

**Unit 2 Time Advisory**  
This unit should take you approximately 33 hours to complete.  
  
 ☐    Subunit 2.1: 18 hours  
  
 ☐    Subunit 2.2: 4 hours  
  
 ☐    Subunit 2.3: 7.5 hours  
  
 ☐    Subunit 2.4: 3.5 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   define metric spaces;
-   define open, closed, and bounded sets;
-   define cluster points;
-   define convergence of sequences and prove or disprove the
    convergence of given sequences;
-   prove and use properties of limits;
-   define density;
-   prove standard results about closures, intersections, and unions of
    open and closed sets;
-   define compactness using both open covers and sequences;
-   state and prove the Heine-Borel Theorem;
-   state the Bolzano-Weierstrass Theorem;
-   state and use the Cantor Finite Intersection Property;
-   define Cauchy sequence and prove that specific sequences are Cauchy;
-   define completeness;
-   show that convergent sequences are Cauchy;
-   define limit superior and limit inferior;
-   prove that the set of real numbers, equipped with the standard
    metric, is complete;
-   define convergence of series using the Cauchy criterion;
-   and use the comparison, ratio, and root tests to show convergence of
    series.

**2.1 Metric Spaces** <span id="2.1"></span> 
**2.1.1 Definition** <span id="2.1.1"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 11: Metric
    Spaces”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 11: Metric
    Spaces”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the “Metric Spaces” section on pages
    95-98.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 8: Cantor Diagonalization and Metric Spaces”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 8: Cantor Diagonalization and Metric
    Spaces”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/7/c8uDJt5-ZYM)
    (YouTube)  
      
     Instructions: Please watch the video from the 51-minute mark to the
    end. In this lecture, Professor Su defines metric spaces and gives
    examples. He defines open balls and gives examples of open balls in
    a variety of metrics.  
      
     Watching this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Activity: The Trillia Group: Elias Zakon’s Mathematical Analysis
    I: “Chapter 3: Vector Spaces and Metric Spaces: Section 11: Problems
    on Metric Spaces”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 11: Problems
    on Metric
    Spaces](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please scroll down to page 98, and work through
    problems 1, 9, 11, and 12.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.1.2 Open and Closed Sets** <span id="2.1.2"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 12: Open and
    Closed Sets; Neighborhoods”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 12: Open and
    Closed Sets;
    Neighborhoods](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the “Open and Closed Sets; Neighborhoods”
    section on pages 101-106.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Activity: The Trillia Group: Elias Zakon’s Mathematical Analysis
    I: “Chapter 3: Vector Spaces and Metric Spaces: Section 12: Problems
    on Neighborhoods, Open and Closed Sets”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 12: Problems
    on Neighborhoods, Open and Closed
    Sets](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please scroll down to page 107, and work through
    problems 7, 8, 16, 17, and 18.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.1.3 Bounded Sets** <span id="2.1.3"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 13: Bounded
    Sets; Diameters”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 13: Bounded
    Sets;
    Diameters](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the “Bounded Sets; Diameters” section on
    pages 108-112.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Activity: The Trillia Group: Elias Zakon’s Mathematical Analysis
    I: “Chapter 3: Vector Spaces and Metric Spaces: Section 13: Problems
    on Boundedness and Diameters”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 13: Problems
    on Boundedness and
    Diameters](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please scroll down to page 112, and work through
    problems 2, 4, 11, and 12.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.1.4 Cluster Points** <span id="2.1.4"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 14: Cluster
    Points; Convergent Sequences”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 14: Cluster
    Points; Convergent
    Sequences](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the “Cluster Points; Convergent
    Sequences” section on pages 114-118.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 9: Limit Points” and “Lecture 15: Convergence of
    Sequences”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 9: Limit
    Points”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/8/Ebnoxgp8mLM) (YouTube)
    and [“Lecture 15: Convergence of
    Sequences”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/14/VEx3Ys6JAJo) (YouTube)  
      
     Instructions: Please watch these lectures. In the first lecture,
    Professor Su defines limit (cluster) points and goes through many
    examples. He also defines interior points, open sets, closed sets,
    and closures. In the second lecture, Professor Su defines what it
    means for a sequence to converge.  
      
     Watching these lectures and pausing to take notes should take
    approximately 2 hours and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Activity: The Trillia Group: Elias Zakon’s Mathematical Analysis
    I: “Chapter 3: Vector Spaces; Metric Spaces: Section 14: Problems on
    Cluster Points and Convergence”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces; Metric Spaces: Section 14: Problems on
    Cluster Points and
    Convergence](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please scroll down to page 118, and work through
    problems 5 and 10.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.1.5 Operations on Convergent Sequences** <span id="2.1.5"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 15: Operations
    on Convergent Sequences”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 15: Operations
    on Convergent
    Sequences](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the indicated section on pages 120-123.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 16: Subsequences, Cauchy Sequences”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 16: Subsequences, Cauchy
    Sequences”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/15/kbkvMTGHiQk) (YouTube)  
      
     Instructions: Please watch this lecture through the 30-minute mark.
    In this lecture, Professor Su further explores properties of limits
    of sequences.  
      
     Watching this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Activity: The Trillia Group: Elias Zakon’s Mathematical Analysis
    I: “Chapter 3: Vector Spaces and Metric Spaces: Section 15: Problems
    on Limits of Sequences”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 15: Problems
    on Limits of
    Sequences](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please scroll down to page 123, and work through
    problems 1, 10, 12, 13, and 25.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.1.6 Closed Sets and Density** <span id="2.1.6"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 16: More on
    Cluster Points and Closed Sets; Density”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 16: More on
    Cluster Points and Closed Sets;
    Density](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the “More on Cluster Points and Closed
    Sets; Density” section on pages 135-139.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 10: The Relationship Between Open and Closed
    Sets”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 10: The Relationship Between Open and Closed
    Sets”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/9/6zs_PTUfKAk) (YouTube)  
      
     Instructions: Please watch this lecture, in which Professor Su
    revisits the definition of open and closed sets and some of the
    subtleties involved in manipulating them. He proves standard
    results, such as that the closure of a set is closed and that a set
    is closed if and only if its complement is open. He also
    investigates unions and intersections of open and closed sets. He
    defines what it means for one set to be dense in another set.  
      
     Watching this lecture and pausing to take notes should take
    approximately 1 hour and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Activity: The Trillia Group: Elias Zakon’s Mathematical Analysis
    I: “Chapter 3: Vector Spaces and Metric Spaces: Section 16: Problems
    on Cluster Points, Closed Sets, and Density”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 16: Problems
    on Cluster Points, Closed Sets, and
    Density](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please scroll down to page 140, and work through
    problems 9, 12, and 17.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.2 Compactness** <span id="2.2"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 4: Function Limits and Continuity: Section 6: Compact Sets
    and Section 7: More on Compactness”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 4: Function Limits and Continuity: Section 6: Compact Sets
    and Section 7: More on
    Compactness](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the indicated sections on pages 186-189
    and pages 192-194.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 11: Compact Sets” and “Lecture 12: The
    Relationship of Compact Sets to Closed Sets”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 11: Compact
    Sets”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/10/zeVA74yivyg) (YouTube)
    and [“Lecture 12: The Relationship of Compact Sets to Closed
    Sets”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/11/kkKfRaI-cqs) (YouTube)  
      
     Instructions: Click on the links above, and watch these
    lectures. In the first lecture, Professor Su defines compactness
    from the topological perspective (*e.g.,* the way it is defined in
    the reading of Zakon’s Section 4.7 – every open cover of the set
    must have a finite subcover). This is because in his course he
    develops this concept before discussing the convergence of
    sequences. He also (in essence) defines what it means for a set to
    be relatively open with respect to another set. He proves that
    compact sets are bounded in Euclidean space. In the second lecture,
    Professor Su proves that compact sets are closed in Euclidean space.
    He proves that nested closed intervals in R have nonempty
    intersection. He also proves that R is uncountable.  
      
     Also, note that Professor Su will touch on sequential compactness
    in the lecture for sub-subunit 2.3.2. In this lecture and the one
    that follows, he uses the open-cover definition.  
        
     Watching these lecture sand pausing to take notes should take 2
    hours and 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 13: Compactness and the Heine-Borel Theorem”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 13: Compactness and the Heine-Borel
    Theorem”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/12/AQHVdiXRXQA) (YouTube)  
      
     Instructions: Please watch this lecture, in which Professor Su
    proves that closed, bounded intervals on the real line are compact.
    He then proves the Heine-Borel Theorem (this is exercise 10 in
    section 4.6 of Zakon’s book). He states a version of the
    Bolzano-Weierstrass Theorem (which will be discussed in the reading
    under sub-subunit 2.3.1 for this course) and the Cantor Finite
    Intersection Property.  
      
     Watching this lecture and pausing to take notes should take 1 hour
    and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.3 Subsequences, Cauchy Sequences, and Completeness** <span
id="2.3"></span> 
**2.3.1 Cauchy Sequences and Completeness** <span id="2.3.1"></span> 
-   **Reading: The Trillia Group: Elias Zakon’s Mathematical Analysis I:
    “Chapter 3: Vector Spaces and Metric Spaces: Section 17: Cauchy
    Sequences; Completeness”**
    Link: The Trillia Group: Elias Zakon’s *Mathematical Analysis I*:
    [“Chapter 3: Vector Spaces and Metric Spaces: Section 17: Cauchy
    Sequences;
    Completeness](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)[”](http://www.saylor.org/site/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Please read the “Cauchy Sequences; Completeness”
    section on pages 141-144.  
      
     Terms of Use: *Mathematical Analysis I* was written by Elias Zakon
    and relicensed under a [Creative Commons-By Attribution 3.0 Unported
    Licencse](http://creativecommons.org/licenses/by/3.0/) as part of
    the Saylor Foundation’s Open Textbook Challenge. It is attributed to
    the Trillia Group and Elias Zakon.

**2.3.2 Limits Superior and Inferior and the Bolzano-Weierstrass
Theorem** <span id="2.3.2"></span> 
-   **Reading: University of California, San Diego: Jiri Lebl’s *Basic
    Analysis: Introduction to Real Analysis*: “Section 2.3: Limit
    Superior, Limit Inferior, and Bolzano-Weierstrass”**
    Link: University of California, San Diego: Jiri Lebl’s *Basic
    Analysis: Introduction to Real Analysis*: [“Section 2.3: Limit
    Superior, Limit Inferior, and
    Bolzano-Weierstrass”](http://www.saylor.org/site/wp-content/uploads/2013/06/MA241-BasicAnalysis-JiriLebl-6.3.2013.pdf)
    (PDF)  
      
     Instructions: Please read “Limit Superior, Limit Inferior, and
    Bolzano-Weierstrass” on pages 61-66.  
      
     Terms of Use: The article above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Jiri Lebl and the original version can be found
    [here](http://www.jirka.org/ra/realanal.pdf).

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 16: Subsequences, Cauchy Sequences” and “Lecture
    17: Complete Spaces”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 16: Subsequences, Cauchy
    Sequences”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/15/kbkvMTGHiQk) (YouTube)
    and [“Lecture 17: Complete
    Spaces”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/16/6-PSUkwGnnA) (YouTube)  
      
     Instructions: Please watch both lectures. Watch “Lecture 16:
    Subsequences, Cauchy Sequences” from the 30-minute mark to the end;
    watch all of “Lecture 17: Complete Spaces”. In the first lecture,
    Professor Su defines subsequences and proves several important
    results about them. Note the definition of sequential compactness at
    time 43:50. He proves the Bolzano-Weierstrass Theorem. He defines
    Cauchy sequence and completeness. In the second lecture, Professor
    Su proves that compact metric spaces are complete. He also proves
    that Euclidean space is complete. He constructs the completion of a
    metric space. He discusses bounded sequences and monotonic sequences
    and proves that bounded, monotonic sequences converge. He defines
    limit superior and limit inferior and proves several results about
    them.  
      
     Watching these lectures and pausing to take notes should take
    approximately 1 hour and 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.4 Series** <span id="2.4"></span> 
-   **Reading: University of California, San Diego: Jiri Lebl’s *Basic
    Analysis: Introduction to Real Analysis*: “Section 2.5: Series”**
    Link: University of California, San Diego: Jiri Lebl’s *Basic
    Analysis: Introduction to Real Analysis*: [“Section 2.5:
    Series”](http://www.saylor.org/site/wp-content/uploads/2013/06/MA241-BasicAnalysis-JiriLebl-6.3.2013.pdf)
    (PDF)  
      
     Instructions: Please read “Series” on pages 72-81.  
      
     Terms of Use: The article above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Jiri Lebl and the original version can be found
    [here](http://www.jirka.org/ra/realanal.pdf).

-   **Lecture: YouTube: Harvey Mudd College: Professor Francis Su’s Real
    Analysis: “Lecture 18: Series” and “Lecture 19: Series Convergence
    Tests, Absolute Convergence”**
    Link: YouTube: Harvey Mudd College: Professor Francis Su’s *Real
    Analysis*: [“Lecture 18:
    Series”](http://www.youtube.com/watch?v=v5CHTVDiMkQ) (YouTube)
    and [“Lecture 19: Series Convergence Tests, Absolute
    Convergence”](http://www.youtube.com/user/HarveyMuddCollegeEDU#p/u/18/tt430qiyIds) (YouTube)  
      
     Instructions: Please watch these lectures. In the first lecture,
    Professor Su defines series convergence using partial sums (a.k.a.
    the Cauchy Criterion). He validates the Comparison Test. He
    discusses the geometric series. In the second lecture, Professor Su
    discusses further tests for convergence, along with the definition
    of absolute convergence. He gives the ratio and root tests. He
    defines power series. He discusses summation by parts.  
      
     Watching these lectures and pausing to take notes should take
    approximately 2 hours and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


