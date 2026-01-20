# CAS CS 237 - Probability in Computing - Spring 2026

---

## Course Staff

<table class="staff-table">
    <tr>
        <td class="role">Instructors</td>
        <td>
            <a href="https://nathan-klein.github.io/">Prof. Nathan Klein</a><br>
            <a href="https://cs-people.bu.edu/januario/">Prof. Tiago Januario</a>
        </td>
    </tr>

    <tr>
        <td class="role">Teaching Fellows</td>
        <td>
            <a href="https://cs-people.bu.edu/taduy/">Ta Duy Nguyen</a><br>
        </td>
    </tr>

    <tr>
        <td class="role">Teaching Assistant</td>
        <td>
            <a href="https://www.linkedin.com/in/steve-choi-75b9a1273/">Steve Choi</a><br>
            <a href="https://www.linkedin.com/in/daniel-matuzka-3a1185295/">Daniel Matuzka</a><br>
        </td>
    </tr>

    <tr>
        <td class="role">Course Assistants</td>
        <td>
            
            <!-- <a href="https://www.linkedin.com/in/letitia-caspersen">Letitia Caspersen</a><br> -->
            
            Vi Tjiong<br>
            <a href="https://www.linkedin.com/in/syuhan/">Sarah Yuhan</a><br>
            <a href="https://www.linkedin.com/in/changyoon-oh-903b42352">Yoon Oh</a>
        </td>
    </tr>
</table>
---

## Communication and Office hours

<div style="display: flex;">
  <div style="flex: 1; padding-right: 10px;">
  <ul>
      <li><a href="https://piazza.com/" target="_blank">Piazza</a> is the <strong>primary platform</strong> for all online discussions, questions, and answers.
        <ul>
          <li>Use <strong>private posts</strong> for sensitive or specific questions regarding your solutions or personal matters.</li>
          <li><b>Do not send emails</b> to the course staff.</li>
        </ul>
      </li>
      <li>We aim to maintain a <strong>positive and inclusive atmosphere</strong> on all course platforms.</li>
      <li>If you need <strong>special accommodations</strong> or are facing <strong>unusual circumstances</strong> during the semester, please reach out to an instructor privately via Piazza as early as possible.
        <ul>
          <li>For accommodations, forward relevant documentation from <a href="https://www.bu.edu/disability/">Disability and Access Services</a>.</li>
        </ul>
      </li>
      <li>Your <strong>suggestions</strong> for improving the course are always encouraged and appreciated.</li>
    </ul>
  </div>
  <div style="flex: 1; padding-left: 10px;">
<img src="email.gif" style="width:95%;">
  </div>
</div>



*   Check our [Google Calendar](https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FNew_York&showPrint=0&mode=WEEK&src=Y182Y2I2M2Q3M2Y0NzQxMTU1Yzc4ZTI0MWU3OGI3MWIzZDc2NDA3ZTNhMGZlNjdlODlkOTIzMjVlMjNkMjFlMWY3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%237986cb&color=%230b8043) for hour Office hours.

<center>
<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FNew_York&showPrint=0&mode=WEEK&src=Y182Y2I2M2Q3M2Y0NzQxMTU1Yzc4ZTI0MWU3OGI3MWIzZDc2NDA3ZTNhMGZlNjdlODlkOTIzMjVlMjNkMjFlMWY3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%237986cb&color=%230b8043" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</center>

---
## Prerequisites

*   [CS 131 - Combinatoric Structures](https://www.bu.edu/academics/cas/courses/cas-cs-131/)
*   [MA 123 - Calculus I](https://www.bu.edu/academics/cas/courses/cas-ma-123/)
*   [CS 111 - Introduction to Computer Science I](https://www.bu.edu/academics/cas/courses/cas-cs-111/)

We assume good working knowledge of elementary set theory and counting, elementary calculus (i.e., integration and differentiation), and programming in Python.

---
## Syllabus

Introduction to basic probabilistic concepts and methods used in computer science. Develops an understanding of the crucial role played by randomness in computing, both as a powerful tool and as a challenge to confront and analyze. Emphasis on rigorous reasoning, analysis, and algorithmic thinking. This course fulfills a single unit in each of the following BU Hub areas: Quantitative Reasoning II, Critical Thinking.

---
## Course structure

*   Attendance in lectures and discussion is mandatory
*   The two lecture sections of the course will be treated as one class. However, you must attend the section you are signed up for (please discuss with us if there is an issue).
*   The content of the two lectures is identical, and assignments will be shared.

---
## Textbooks

You can access both books for free or support the authors by purchasing the books.

*   (LLM) [Mathematics for Computer Science](https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf) by Eric Lehman, Tom Leighton, and Albert Meyer.
*   (P) [Introduction to Probability, Statistics, and Random Processes](https://www.probabilitycourse.com/) by Hossein Pishro-Nik.
*   (CLRS) Cormen, Leiserson, Rivest, and Stein. Introduction to Algorithms, Fourth Edition, MIT Press.

---
## Schedule

This schedule is subject, and likely, to change as we progress through the semester. Reading chapters are from the [first textbook](https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf) (LLM) or from the [second textbook](https://www.probabilitycourse.com/) (P), referred to by the acronyms of the author names.

<table>
    <thead>
        <tr>
            <th>Date / Lec</th>
            <th>Agenda (Topics, Readings, Homework)</th>
            <th>Instr.</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td> <strong>Lec 1</strong><br> Tuesday<br> Jan 20 </td>
            <td>
                Course information<br> 
                Tips to succeed<br> Random experiments<br> 
                Sample spaces, events<br> 
                <!-- <ahref="./slides/cs237L01-annotated.pdf">[Slides with notes]</a><br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter1/1_0_0_introduction.php">P 1.1</a>, <a
                        href="https://www.probabilitycourse.com/chapter1/1_2_0_review_set_theory.php">P 1.2</a>, <a
                        href="https://ocw.mit.edu/courses/18-05-introduction-to-probability-and-statistics-spring-2014/250d5dfd399a5612d232cc337fc51fa9_MIT18_05S14_Reading1b.pdf">OB
                        1B</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> <a
                        href="https://jupyter.org/try-jupyter/lab/">Jupyter Lab</a>, <a href="lec01.ipynb">Your first
                        Jupyter Notebook</a>, <a href="collaboration-policy.pdf">Collaboration & Honesty Policy</a>
                </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 2</strong><br> Thurday<br> Jan 22 </td>
            <td>
                Probability function<br> 
                Symmetry<br> 
                Probability axioms <br> 
                <!-- <a href="./slides/cs237L02-annotated.pdf">[Slides with notes]</a> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.17.1">LLM 17.1</a>, <a
                        href="https://www.probabilitycourse.com/chapter1/1_3_1_random_experiments.php">P 1.3.1-1.3.3</a>
                </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw01 out </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 3</strong><br> Tuesday <br> Jan 27 </td>
            <td>
                Probability rules<br> 
                Computing probabilities <br> 
                <!-- <a href="./slides/cs237L03-annotated.pdf">[Slides with notes]</a><br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.17.3">LLM 17.3</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.17.5">LLM 17.5</a>, <a
                        href="https://www.probabilitycourse.com/chapter2/2_1_0_counting.php">P 2</a> </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 4</strong><br> Thurday <br> Jan 29 </td>
            <td>
                Tree diagrams<br> 
                The Monty Hall problem<br> 
                <!-- <a href="./slides/cs237L04-annotated.pdf">[Slides with notes]</a><br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.17.2">LLM 17.2</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.18.1">LLM 18.1.2</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw02 out </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 5</strong><br> Tuesday<br> Feb 3 </td>
            <td>
                Continuous Probability Spaces<br> 
                Anomalies with Continuous Probability <br>
                <!-- <a href="./slides/cs237L05-annotated.pdf">[Slides with notes]</a><br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter1/1_3_5_continuous_models.php">P 1.3.5</a> </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.probabilitycourse.com/videos/chapter1/video1_4.php">Video</a>, <a
                        href="https://www.youtube.com/watch?v=ZA4JkHKZM50">Why “probability of 0” does not mean
                        “impossible”</a> </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 6</strong><br> Thursday<br> Feb 5 </td>
            <td>
                Random variables<br> 
                Sum of random variables<br>
                Definition and examples <br>
                <!-- <a href="./slides/cs237L06-annotated.pdf">[Slides with notes]</a><br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.1">LLM 19.1</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_1_1_random_variables.php">P 3.1.1</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_1_2_discrete_random_var.php">P 3.1.2</a>
                </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw03 out </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 7</strong><br> Tuesday<br> Feb 10 </td>
            <td>
                Distribution Functions: PDF and CDF <br>
                <!-- <a href="./slides/cs237L07-annotated.pdf">[Slides with notes]</a><br>  -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter3/3_1_3_pmf.php">P 3.1.3</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_2_1_cdf.php">P 3.2.1</a>, <a
                        href="https://www.probabilitycourse.com/chapter4/4_1_0_continuous_random_vars_distributions.php">P
                        4.1.0</a>, <a href="https://www.probabilitycourse.com/chapter4/4_1_1_pdf.php">P 4.1.1</a> </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.probabilitycourse.com/videos/chapter3/video3_1.php">Video</a> </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 8</strong><br> Thursday<br> Feb 12 </td>
            <td>
                Properties of PDFs and CDFs<br> 
                Functions of random Variables<br>
                <!-- <a href="./slides/cs237L08-annotated.pdf">[Slides with notes]</a><br>  -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter3/3_1_6_solved3_1.php">P 3.1.6</a>, <a
                        href="https://www.probabilitycourse.com/chapter4/4_1_4_solved4_1.php">P 4.1.4</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw04 out </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.probabilitycourse.com/videos/chapter3/video3_1.php">Video</a> </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow"> Tuesday<br> Feb 17 </td>
            <td style="background-color: LightYellow">
                Substitute Monday Schedule of Classes 
                <div class="agenda-item"> Check the <a
                        href="https://calendar.google.com/calendar/u/0/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America/New_York&mode=WEEK&src=Y182Y2I2M2Q3M2Y0NzQxMTU1Yzc4ZTI0MWU3OGI3MWIzZDc2NDA3ZTNhMGZlNjdlODlkOTIzMjVlMjNkMjFlMWY3QGdyb3VwLmcaWVuZGFyLmdvb2dsZS5jb20&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%237986CB&color=%230B8043">Google
                        Calendar</a> for the updated office hour schedule </div>
            </td>
            <td style="background-color: LightYellow"> </td>
        </tr>
        <tr>
            <td> <strong>Lec 9</strong><br> Thursday<br> Feb 19 </td>
            <td>
                <div class="agenda-item"> <span class="topic-title">
                Conditional Probability<br> 
                Pr(⋅ ∣ 𝐸) is a probability function <br>
                Conditional Probability in Tree Diagrams<br> 
                </span> 
                        <!-- <a href="./slides/cs237L09-annotated.pdf">[Slides with notes]</a> -->
                </div>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#chapter.18">LLM 18</a>, <a
                        href="https://www.probabilitycourse.com/chapter1/1_4_0_conditional_probability.php">P 1.4.0</a>
                </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw05 out </div>
                <div class="agenda-item"> <span class="meta-label">Play:</span> <a
                        href="https://www.stem.org.uk/resources/elibrary/resource/440253/card-game-conditional-probability">Game:
                        higher or lower?</a> </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 10</strong><br> Tuesday<br> Feb 24 </td>
            <td>
                Product Rule<br> 
                Law of Total Probability (generalization)<br> 
                Bayes’ Rule <br>
                <!-- <a href="./slides/cs237L10-annotated.pdf">[Slides with notes]</a>  -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter1/1_4_2_total_probability.php">P 1.4.2</a>, <a
                        href="https://www.probabilitycourse.com/chapter1/1_4_3_bayes_rule.php">P 1.4.3</a> </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.youtube.com/watch?v=HZGCoVF3YvM">The geometry of changing beliefs</a>, <a
                        href="https://www.youtube.com/watch?v=R13BD8qKeTg">Veritasium</a> </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 11</strong><br> Thursday<br> Feb 26 </td>
            <td>
                Independent Events<br> 
                Independence for Multiple Events <br>
                <!-- <a href="./slides/cs237L11-annotated.pdf">[Slides with notes]</a><br>  -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.18.7">LLM 18.7</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.18.8">LLM 18.8</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw06 out </div>
                <div class="agenda-item"> Last Day to Drop Standard Courses (without a “W” grade) </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 12</strong><br> Tuesday<br> Mar 3 </td>
            <td> 
                Independence for Random Variables<br>
                Pairwise and Mutual Independence<br>
                <a href="https://en.wikipedia.org/wiki/People_v._Collins">People v. Collins</a><br> 
                <!-- <a href="./slides/cs237L12-annotated.pdf">[Slides with notes]</a> <br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.18.9">LLM 18.9</a>, <a
                        href="https://www.probabilitycourse.com/chapter1/1_4_1_independence.php">P 1.4.1</a> </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.youtube.com/watch?v=rIjIcWeY1X0">Video</a> </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow;"> Thursday<br> Mar 5 </td>
            <td style="background-color: LightYellow;text-align: center;">
                <div class="agenda-item"> 
                <strong>Midterm, in class, during lecture time <br>
                Covers all topics up to Lecture 12 </strong> <br>
                No discussion sections on Friday
                </div>
            </td>
            <td style="background-color: LightYellow;"></td>
        </tr>
        <tr class="special-event">
            <td> Tuesday<br> Mar 10 </td>
            <td style="text-align: center;"> 🌸 <strong>Spring break</strong>🌺 </td>
            <td></td>
        </tr>
        <tr class="special-event">
            <td> Thursday<br> Mar 12 </td>
            <td style="text-align: center;"> 🌼 <strong>Spring break</strong> 🌷 </td>
            <td></td>
        </tr>
        <tr>
            <td> <strong>Lec 13</strong><br> Tuesday<br> Mar 17 </td>
            <td>
            More Independence <br> 
            Expected value of a random variable<br>
            Infinite sums<br> 
                <!-- <a href="./slides/cs237L13-annotated.pdf">[Slides with notes]</a> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.4">LLM 19.4</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_2_2_expectation.php">P 3.2.2</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> Midterm practice problems out </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 14</strong><br> Thursday<br> Mar 19 </td>
            <td>
                Linearity of expectation<br>
                Law of the unconscious statistician<br> 
                <!-- <a href="./slides/cs237L14-annotated.pdf">[Slides with notes]</a> <br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.5">LLM 19.5</a>, <a
                        href="https://www.probabilitycourse.com/chapter6/6_1_2_sums_random_variables.php">P 6.1.2</a>
                </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw07 out </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> Midterm practice solutions out </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 15</strong><br> Tuesday<br> Mar 24 </td>
            <td>
                Conditional expectation<br> 
                Linearity of conditional expectation <br>
                Law of total expectation<br> 
                <!-- <a href="./slides/cs237L15-annotated.pdf">[Slides with notes]</a> <br> -->
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.4">LLM 19.4.1</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_2_3_functions_random_var.php">P 3.2.3</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.4">LLM 19.4.6</a> </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 16</strong><br> Thursday<br> Mar 26 </td>
            <td>
                Variance<br> 
                Standard deviation<br> 
                Variance properties<br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.20.3">LLM 20.3</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_2_4_variance.php">P 3.2.4</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw08 out </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.probabilitycourse.com/videos/chapter3/video3_9.php">Video</a> </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 17</strong><br> Tuesday<br> Mar 31 </td>
            <td>
            Discrete distributions: <br>
            - Bernoulli, <br>
            - Uniform, <br>
            - Binomial
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.3">LLM 19.3.1</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.3">LLM 19.3.2</a>, <a
                        href="https://www.probabilitycourse.com/chapter3/3_1_5_special_discrete_distr.php">P 3.1.5</a>
                </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 18</strong><br> Thursday<br> Apr 2 </td>
            <td>
                Discrete distributions: <br>
                - Geometric and its properties <br>
                - Coupon collector's problem<br> 
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.19.5">LLM 19.5.4</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw09 out </div>
            </td>
            <td>TJ</td>
        </tr>
        <tr>
            <td> <strong>Lec 19</strong><br> Tuesday<br> Apr 7 </td>
            <td>
                Reservoir sampling<br> 
                Negative Binomial <br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://en.wikipedia.org/wiki/Reservoir_sampling">Wikipedia</a> </div>
                <div class="agenda-item"> <span class="meta-label">Watch:</span> <a
                        href="https://www.youtube.com/watch?v=BstloCx8KDk">Stand-up Maths</a> </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 20</strong><br> Thursday<br> Apr 9 </td>
            <td>
                Markov inequality<br> 
                Chebyshev inequality<br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.20.1">LLM 20.1</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.20.2">LLM 20.2</a>, <a
                        href="https://www.probabilitycourse.com/chapter6/6_2_2_markov_chebyshev_inequalities.php">P
                        6.2.2</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw10 out </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 21</strong><br> Tuesday<br> Apr 14 </td>
            <td>
                Applications of Markov and Chebyshev's inequalities<br> 
                Continuous Uniform Distribution <br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.20.1">LLM 20.1.1</a>, <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.20.2">LLM 20.2.1</a> </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 22</strong><br> Thursday<br> Apr 16 </td>
            <td>
                Normal distribution <br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://cs-people.bu.edu/aene/cs237fa21/mcs.pdf#section.20.2">LLM 20.2.2</a>, <a
                        href="https://www.probabilitycourse.com/chapter4/4_2_3_normal.php">P 4.2.3</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw11 out </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 23</strong><br> Tuesday<br> Apr 21 </td>
            <td>
                Exponential distribution <br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter4/4_2_2_exponential.php">P 4.2.2</a>, <a
                        href="https://www.probabilitycourse.com/chapter11/11_1_2_basic_concepts_of_the_poisson_process.php">P
                        11.1.2</a> </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 24</strong><br> Thursday<br> Apr 23 </td>
            <td>
                Poisson Process <br>
                Poisson Distribution <br>
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://www.probabilitycourse.com/chapter11/11_1_2_basic_concepts_of_the_poisson_process.php">P
                        11.1.2</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> hw12 out<br> Final Practice Problems out
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 25</strong><br> Tuesday<br> Apr 28 </td>
            <td>
                Central Limit Theorem <br>
                Law of Large Numbers <br>
                <a href="https://my-bu.bluera.com/">Course evaluation</a> 
                <div class="agenda-item"> <span class="meta-label">Read:</span> CLRS 8.4 </div>
                </div>
            </td>
            <td>NK</td>
        </tr>
        <tr>
            <td> <strong>Lec 26</strong><br> Thursday<br> Apr 30 </td>
            <td>
                Applied probability <br>
                Chernoff bounds <br>
                <a href="https://my-bu.bluera.com/">Course evaluation</a> 
                <div class="agenda-item"> <span class="meta-label">Read:</span> <a
                        href="https://en.wikipedia.org/wiki/Reservoir_sampling">Wiki</a> </div>
                <div class="agenda-item"> <span class="meta-label">Do:</span> Final Practice Solutions out </div>
            </td>
            <td>NK</td>
        </tr>
        <tr class="special-event">
            <td> Friday<br> May 1 </td>
            <td> Study Period begins - no discussion sections</td>
            <td>--</td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow"> Monday<br> May 4 </td>
            <td style="background-color: LightYellow;text-align: center;"> Final Exam Week Begins </td>
            <td style="background-color: LightYellow;text-align: center;"> </td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow"> Tuesday<br> May 5 </td>
            <td style="background-color: LightYellow;text-align: center;"> Final Exam for A2 Section <br> 12:00 - 2:00pm in KCB 106</td>
            <td style="background-color: LightYellow;text-align: center;"></td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow"> Thursday<br> May 7 </td>
            <td style="background-color: LightYellow;text-align: center;"> Final Exam for A1 Section <br> 9:00 - 11:00am in KCB 106</td>
            <td style="background-color: LightYellow;text-align: center;"></td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow"> Friday<br> May 8 </td>
            <td style="background-color: LightYellow;text-align: center;"> Final Exam Week Ends </td>
            <td style="background-color: LightYellow;text-align: center;"> </td>
        </tr>
    </tbody>
</table>

<!--We have prearranged the following date and time for students with final exam conflict:

* Alternative Final exam date: December 16th
* Time: 3:00 PM – 5:00 PM
* Location: STHB19

Students with exam accommodations, regardless or their final exam conflict, will take the final exam at same day and initial time of the other students at CDS 801.
-->

---
## Participation and Attendance

*   Participation in lecture will be tracked with [Top Hat](https://tophat.com). We will start using this the second week of classes.
*   Participation in discussion labs will be tracked with [Top Hat](https://tophat.com) as well.
*   You will get full participation points if you answer at least 85% of the possible [Top Hat](https://tophat.com) questions. You do not need to answer correctly, although we encourage you to use these questions as exam preparation.
*   You will get full attendance points if you attend at least 85% of the discussion labs.
*   If you end up with x% points, where x < 85, you will get x/85 of the points.
*   Most of the material covered in lectures and labs can be found in our textbooks. Read them!
*   While our textbook will be very helpful, it is an imperfect substitute for in-class learning, which is the fastest (and easiest) way to learn the material.
*   In all cases, you are responsible for being up to date on the material.

---
## Homework Policy

*   **Submission:** Weekly assignments are posted on Fridays and due by **Thursday at 9:00 PM ET** via [Gradescope](https://www.gradescope.com/). A 3-hour grace period is allowed; submissions after this period will not be accepted.
*   **Content:** Provide step-by-step explanations for your answers. Submissions with only answers will receive minimal credit.
*   **Formatting:** Submit solutions as **one single PDF file** with high-quality images. Illegible submissions will receive a 0. We recommend using [Dropbox](https://www.dropbox.com/referrals/AABXucmmhueiq5iaPPSTVfnTpOeddYmso_0?src=global9) for scanning.
*   **Gradescope Page Selection:** Correctly select the pages for each problem on Gradescope. Failure to do so will result in a 10% penalty. If you don't have a solution, note "No solution provided."
*   **Late Policy:** You may use up to 3 grace periods without penalty. After that, each late submission incurs a 1% penalty.
*   **Dropped Homework:** The lowest homework grade will be dropped after penalties are applied. (Note that the intent of this is to allow you leeway on one *emergency* situation. Do not simply use your free dropped homework because you feel like it.)
*   **Academic Integrity and Collaboration:**
    *   The [Collaboration & Honesty Policy](collaboration-policy.pdf) outlines the rules of collaboration and penalties for cheating. All students are required to read, sign, and submit this document to Gradescope.
    *   Submitting identically worded answers, including pseudocode, is a **serious offense** and will be reported to the Dean's Office ([BU Academic Conduct Code](https://www.bu.edu/academics/policies/academic-conduct-code/#VI)).
    *   Using ChatGPT or similar AI for homework solutions violates the [Collaboration & Honesty Policy](collaboration-policy.pdf). 
    *   You are not required to cite material from the course textbook, lectures, discussion notes, or information provided by course staff.
    *   For any other external information, **a proper citation is required**. Failure to cite constitutes plagiarism.
    *   Explicitly searching for problem answers online or from individuals not enrolled in the current semester's class is strictly forbidden.
    *   If you receive help on Piazza or during office hours from instructors for specific problems, you must list them as collaborators.
*   **Partial Submissions:** Submitting partial work is acceptable if you cannot fully complete an assignment; avoid missing the deadline entirely.
* **The instructors retain the right to oral explanation of any student work submitted for a grade**. If the student cannot explain the work they have submitted, the instructor will assign a grade of 0 on the entire assignment in question.

---
## Exams

*   Both exams will consist of problem-solving and short questions about the material.
*   Each exam duration and their locations are given in the course schedule.
*   The content of the final is cumulative.
*   No collaboration whatsoever is permitted on exams, **any violation will be reported to the College.**

---
## Quizzes

*   There will be four quizzes based on flashcards that will be posted weekly on Piazza. The quiz dates are posted on the schedule. The quizzes are all cumulative and will be simple short answers based on the flashcards. Quizzes will be held at the beginning of class and will last 10-15 minutes.
*   Your lowest quiz score will be dropped. Similar to the homework, the intent of this is to give you leeway in an emergency situation.
*   We use [Anki](https://apps.ankiweb.net/) for flashcards. You can download a free app at that link. We will also post the flashcards in plaintext if you prefer to print them out or just look at them on a website.

---
## Grading

The course grade will be calculated as follows:

*   5% class participation
*   5% lab attendance
*   10% quizzes
*   20% weekly homework assignments
*   25% in-class midterm exam
*   35% in-class final exam. **Don't make any travel plans before knowing all dates of your final exams.**
*   **Incompletes for this class will be granted based on** [CAS Policy](https://www.bu.edu/cas/faculty-staff/instructors-guide/incomplete-grades/).
*   **Note:** <u>Optional homework problems do not count towards your course grade</u>, but we will look at how you did on them if you ask for a recommendation letter.

---
## Regrade Policy

*   Regrade requests can be submitted up to one week (7 days) after grades for a given assignment have been posted (except the final exam).
*   You must request a regrade via Gradescope, _**NOT** through email_.
*   When we regrade a problem, your score may go up or down.

---
## AI Policy

* As stated above, you may not use large language models like ChatGPT or Gemini to provide homework solutions. However, you may use them to help clarify concepts, discuss homework problems *after you have submitted and the deadline has passed*, or similar. Be wary, though, of hallucinations. It is good to double check any information you receive from LLMs with a reliable source.

---
## Miscellaneous

**LaTeX resources**

*   [TexShop](http://pages.uoregon.edu/koch/texshop/) is a latex editor for the Mac platform;
*   [TexNiCenter](http://www.texniccenter.org/) is a text editor for Windows;
*   [Overleaf](https://www.overleaf.com/) is a web-based latex system (that allows you to avoid latex installation on your machine).
*   Not so short [intro to latex](https://tobi.oetiker.ch/lshort/lshort.pdf);
*   A [latex tutorial](http://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf).

**Homework template files**: [tex](sample-hw-solution.tex), [pdf](sample-hw-solution.pdf), [jpg](example-hw-image.jpg).

---
## FAQ

Many common questions have already been answered. Before emailing, posting on Piazza, or asking in class, please try the following:

1. **Start with the syllabus.** It answers an impressive number of questions about deadlines, policies, office hours, and grading. **If you’re still unsure, feel free to consult an LLM.** Copy-pasting the syllabus and asking “What is the policy on X?” is often faster than waiting for a reply—and helps keep Piazza focused on course content.

2. **The course is taken as designed.** Assignments and deadlines apply uniformly to everyone, except where formal accommodations are documented. See #1.

3. **Missed a class?** Something important was probably covered. Please check the posted materials and ask a classmate before reaching out.  See #1.

4. **Dates and deadlines** have been posted since Day 1 (in multiple places). Keeping track of them is part of the course.  See #1.

5. **Office hours exist!** They’re a great place for questions about concepts, feedback, or anything not already answered in the syllabus.  See #1.

6. **Extensions are not granted.** Instead, the course includes "grace periods" for flexibility—please use them wisely.  See #1.

Reading the syllabus (or asking an LLM to summarize it for you) will save everyone time—including you.  See #1.