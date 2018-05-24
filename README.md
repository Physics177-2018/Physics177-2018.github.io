## Physics 177: Computational Physics

[Course webpage](https://physics177-2018.github.io/) (this page)  
[Syllabus](https://github.com/Physics177-2018/Syllabus)  
[![Join the chat at https://gitter.im/Physics177-2018/Lobby](https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg
)](https://gitter.im/Physics177-2018/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  

If you are taking this class, you already have a solid grasp of 'pen and paper' physics. Modern physics, however, often requires tools beyond 'pen and paper' in two ways:
1. Large data sets that can require sophisticated processing and analysis.  
2. Intractable calculations, for example nonlinear systems or high-dimensional phase spaces.  

This is a crash course in learning to deal with data in physical systems and numerical solutions of problems using computers. This is neither a computer science course on algorithms nor a data-based lab course, but it is somewhere in between. 

## Homework

Students: Please use GitHub classroom, use the "[submit]" link to make a private repository where you can submit homework

* [Homework 1a (short)](https://github.com/Physics177-2018/Homework_1a) Due Thursday, 5 April (submit by e-mail or in class)
* [Homework 1b (long)](https://github.com/Physics177-2018/Homework_1b/blob/master/Homework%201b.ipynb) Due Tuesday, 10 April
* [Homework 2a (short)](https://github.com/Physics177-2018/Homework_2a) Due Thursday, 12 April [[submit](https://classroom.github.com/a/pHhYhL8W)]
* [Homework 2b (long)](https://github.com/Physics177-2018/Homework_2b), Due Tuesday, 17 April [[submit](https://classroom.github.com/a/dmOWtBBX)]
* [Homework 3a (short)](https://github.com/Physics177-2018/Homework_3a), Due Thursday, 19 April [[submit](https://classroom.github.com/a/P9Zp5S8n)]
* [Homework 3b (long)](https://github.com/Physics177-2018/homework_3b), Due Tuesday, 24 April [[submit](https://classroom.github.com/a/H6AZfUa1)]
* [Homework 4a (short)](https://github.com/Physics177-2018/homework_4a), Due Thursday, 26 April [[submit](https://classroom.github.com/a/3yrIcwGQ)]
* [Homework 4b (long)](https://github.com/Physics177-2018/Homework_4b), Due Tuesday, 1 May [[submit](https://classroom.github.com/a/OrgJMHuw)]
* [Homework 5a (short)](https://github.com/Physics177-2018/Homework_5a), Due Thursday, 3 May [[submit](https://classroom.github.com/a/-5wZ6eLC)]
* [Homework 5b (long)](https://github.com/Physics177-2018/Homework_5b), Due Tuesday, 5 May [[submit](https://classroom.github.com/a/Rw5BCjeE)]
* [Homework 6a (short)](https://github.com/Physics177-2018/homework_6a), Due Thursday, 10 May [[submit](https://classroom.github.com/a/bX1r0cbZ)]
* [Homework 6b (long)](https://github.com/Physics177-2018/homework_6b), Due Tuesday, 15 May [[submit](https://classroom.github.com/a/PTzsXusT)]
* [Homework 7a (short)](https://github.com/Physics177-2018/Homework_7a), Due Thursday, 17 May [[submit](https://classroom.github.com/a/CR-QNQGR)]
* [Homework 7b (long)](https://github.com/Physics177-2018/Homework_7b), Due Tuesday, 22 May [[submit](https://classroom.github.com/a/JncLVFhd)]
* [Homework 8a (short)](https://github.com/Physics177-2018/homework_8a), Due Thursday, 24 May [[submit](https://classroom.github.com/a/4yAogNmo)]


## Midterm Presentations

Schedule
* 5/15: Presentations 1-5
* 5/17: Presentations 6-9
* 5/22: Presentations 10-13
* 5/24: Presentations 13-17
  
  
   
| Slot | Name | Topic |
|----|---------|-----------------------|
| 1  | Julian  | Binary Search         |
| 2  | Gus     | Stacks                |
| 3  | Nick    | Divide & Conquer      |
| 4  | Bre     | Quicksort             |
| 5  | Steven  | Hash Table            |
|----|---------|-----------------------|
| 6  | Miriam  | Breadth First Graph   |
| 7  | Cindy   | Breadth First + Queue |
| 8  | Adam    | Trading for a Piano   |
| 9  | Van     | Greedy Algorithm      |
|----|---------|-----------------------|
| 10 | Tiffany | Set Covering          |
| 11 | Stephen | Traveling Salesperson |
| 12 | James   | Dynamic Programming   |
| 13 | Jeremy  | Longest Substring     |
|----|---------|-----------------------|
| 14 | Dallas  | K-Nearest Neighbors   |
| 15 | Bran    | Regression            |
| 16 | Trevor  | TBA                   |
| 17 | Quentin | TBA                   |







## Grades

The latest grade sheet is available [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQXeVv39Z9HfxOuAsAuf9HDCsY2b9lst-AaIZAJkF1nA3ATH1vkFhAy_AA1jY-4XspTcXHwYwEd9xz_/pub?gid=1181372918&single=true&output=pdf) (pdf) or [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQXeVv39Z9HfxOuAsAuf9HDCsY2b9lst-AaIZAJkF1nA3ATH1vkFhAy_AA1jY-4XspTcXHwYwEd9xz_/pubhtml?gid=1181372918&single=true) (web). The grades are anonymized and listed according to your assigned P177 **student key number**.

## Week 1

This week we settled into the class. Some students are having trouble with registering, so if you're not yet registered, please don't wait until the last minute in case there are problems. (There's something weird going on with the course registration system.)

**[Lecture 1](https://github.com/Physics177-2018/Lecture_01)**: A soft introduction to the class. Why does "computational physics" exist, anyway? Is it different from "real physics"? The Golden Rule for this class: *Professor Tanedo regrets cannot help you with technical computer problems*. Please make time to get your system up and running---but once you're in a Jupyter notebook, it should be smooth sailing. Index card: name / SID / year / programming background / anything I should know about you.

**[Lecture 2](https://github.com/Physics177-2018/Lecture_02)**: Using GitHub. By the way, here's an [example for how to best look for resources online](http://bfy.tw/DYY6). The discussion on rounding error roughly follows the [Python 3 Tutorial, section 15](https://docs.python.org/3/tutorial/floatingpoint.html). More on representation of numbers: 
- [What Every Programmer Should Know About Floating-Point Arithmetic](http://floating-point-gui.de/)
- [You're Going To Have To Think!](https://accu.org/index.php/journals/1702)
- [Floating Point Representation and Rounding Error (YouTube)](https://www.youtube.com/watch?v=wbxSTxhTmrs)

## Week 2

**[Lecture 3](https://github.com/Physics177-2018/Lecture_03)**: Basic integration using Riemann sums, installing packages. 

**[Lecture 4](https://github.com/Physics177-2018/Lecture_04)**: Integration with trapezoids and parabolas.

## Week 3

*Note: there is NO CLASS on Tuesday, April 17. Homework is still due!*

**[Lecture 5](https://github.com/Physics177-2018/Lecture_05)**: Errors on integrals. What is a reasonable "maximum number of slices" when integrating? Comparing rounding error (numerical precision) to approximation error. 

## Week 4

**[Lecture 6](https://github.com/Physics177-2018/Lecture_06)**: Ordinary differential equations. Runge-Kutta.

**[Lecture 7](https://github.com/Physics177-2018/Lecture_07)**: A peek at RK4, a low-pass filter, and something rotten with energy conservation.

## Week 5

*Note: there is NO CLASS on Tuesday, May 1st. Homework is still due!*

**[Lecture 8](https://github.com/Physics177-2018/Lecture_08)**: Leap-frog, boundary value problems, partial differential equations


## Week 6

**[Lecture 9](https://github.com/Physics177-2018/Lecture_09)**: Partial differential equations, Monte Carlo

**[Lecture 10](https://github.com/Physics177-2018/Lecture_10)**: Buffon's needle, Markov chains

## Week 7 

*Note: we will have a make up lecture on Monday, May 14*

**[Lecture 11](https://github.com/Physics177-2018/Lecture_11)**: Statistical Mechanics (see Lec 10 for a clean version of the code)

**[Lecture 12](https://github.com/Physics177-2018/Lecture_12)**: Review: statistical mechanics sucks

**[Lecture 13](https://github.com/Physics177-2018/Lecture_13)**: Metropolis

## Week 8

*Note: we will have a make up lecture on Wednesday, May 23*

**[Lecture 14](https://github.com/Physics177-2018/Lecture_14)**: Simulated Annealing, traveling salesperson

**[Lecture 15](https://github.com/Physics177-2018/Lecture_15)**: Ising model theory

**[Lecture 16](https://github.com/Physics177-2018/Lecture_16)**: Ising model simulation



## Miscellaneous

* [2017 Course](https://github.com/Physics177-2017)
* [29 common beginner Python errors on one page](https://pythonforbiologists.com/29-common-beginner-errors-on-one-page/) via [pythonforbiologists.com](https://pythonforbiologists.com)
