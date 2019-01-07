Welcome to E110!  "Engineering Computing Architecture" is about how computers are built from simpler components, and how they encode information into physical parts.  Along the way, we will also cover the Linux shell, Hardware Description Languages (HDL) and intermediate Python programming.

# Prerequisites
Students should have already taken ENGR-E 101 Innovation and Design: https://registrar.indiana.edu/browser/soc4192/ENGR/ENGR-E101.shtml

Students should also come to E110 prepared with:
- intermediate computer literacy
- editing, saving, and sharing documents
- working knowledge of Windows, MacOS, and/or Linux
- beginner experience in Python programming language (variables, functions, loops, lists)
- beginner experience with electronics (knowledge of transistors, microcontrollers, voltage, electricity)

# Outcomes
Students will finish E110 with knowledge in:
- fundamentals of digital logic (gates from transistors, complex gates from simple gates)
- how a CPU is constructed, as a system, from simpler components
- number representations (decimal, hexadecimal, binary)
- Linux command-line interface (CLI)
- MyHDL (hardware description language in the form of a Python library)
- intermediate Python

# People

| name            | role       | office     | email           |
|-----------------|------------|------------|-----------------|
| Alex Shroyer    | instructor | Luddy 4148 | ashroyer@iu.edu |
| Juliette Zerick | AI         | Luddy 4125 | jzerick@iu.edu  |
| Daniel Osei     | AI         | Luddy 4125 | dosei@iu.edu    |

# Classroom location, meeting times

| section | lecture           | lab                      | location   |
|---------|-------------------|--------------------------|------------|
|   10678 | (Mon) 10:10-11:00 | (Tues;Thurs) 11:15-12:30 | Luddy 4111 |
|   29714 | (Mon) 11:15-12:05 | (Tues;Thurs) 04:00-05:15 | Luddy 4111 |

# Office Hours

| time                | location   |
|---------------------|------------|
| (Tues) 01:00-02:00  | Luddy 4148 |
| (Thurs) 01:00-02:00 | Luddy 4148 |

# Materials/Textbooks
- Textbook: /The Elements of Computing Systems/ by Noam Nisan and Shimon Schocken. ISBN 978-0262640688
  This course covers chapters 1-6 of the [Nand to Tetris course](https://www.nand2tetris.org/course)
- Python: Use the [docs for Python version 3.7.2 (latest stable release)](https://docs.python.org/3/)
- MyHDL: [Manual](http://docs.myhdl.org/en/stable/) and [Examples](http://www.myhdl.org/docs/examples/)

# Conduct
Lab/Classroom etiquette

1. Respect others who want to work or listen quietly, minimize distractions.
2. No food or open drinks.  Non-spill bottles are OK.
3. Leave the lab at least as clean as you found it.
4. Log out before leaving.

Do your own work
Collaboration for learning and helping each other is encouraged, however all assignments must be exclusively _your own work_.  Cheating results in 0 credit for the assignment, reporting to the Dean, and possible further consequences.

See the [[http://studentcode.iu.edu/responsibilities/academic-misconduct.html][official IU policies]] for more information.

No late work
You may submit multiple times to the Autograder; the highest scoring submission is the one that will be used in grading. No submissions after the deadline will be accepted. Sometimes the Autograder server may be heavily used and respond more slowly, so plan accordingly.

Extensions may be given to _individuals_ in extreme circumstances, such as medical emergencies (Dr. note required). Extensions may be given to the **whole class**, if 5+ students request more time.

# Schedule
See also: (Official IU Calendar for Spring 2019)[https://registrar.indiana.edu/official-calendar/official-calendar-spring.shtml?s=16w]
 <!-- Python interpreter: REPL and CLI usage -->
 <!-- Linux Command-Line Interface (CLI): execute a program with arguments,  -->
 <!-- write a program that takes arguments. -->
 <!-- Digital Inputs and Outputs - valid designs, fan-in, fan-out, electrical characteristics -->

| Date  | Day   | Topic                          | Reading                              | Assignment |
|-------|-------|--------------------------------|--------------------------------------|------------|
| 01/07 | Mon   | Intro, Linux CLI               | [Essential Linux Commands][cli]      | A00a       |
| 01/08 | Tues  | Python CLI, number conversion  | [Python builtin functions][pyth]     | A00b       |
| 01/10 | Thurs | MyHDL, Autograder practice     | MyHDL manual [m1][1] [m2][2] [m3][3] | A00c       |
| 01/14 | Mon   | Boolean Logic                  | Ch.1                                 | A01        |
| 01/15 | Tues  | truth tables                   |                                      |            |
| 01/17 | Thurs | truth tables, continued        |                                      |            |
| 01/21 | Mon   | Gates: 2-input and/or/not/etc. | Ch.1                                 | A02        |
| 01/22 | Tues  | Gates: 16-input and/or/etc.    |                                      |            |
| 01/24 | Thurs | Gates: Mux, Demux              |                                      |            |
| 01/28 | Mon   |                                | Ch.2                                 | A03        |
| 01/29 | Tues  |                                |                                      |            |
| 01/31 | Thurs |                                |                                      |            |
| 02/04 | Mon   |                                | Ch.2                                 | A04        |
| 02/05 | Tues  |                                |                                      |            |
| 02/07 | Thurs |                                |                                      |            |
| 02/11 | Mon   |                                | Ch.3                                 | A05        |
| 02/12 | Tues  |                                |                                      |            |
| 02/14 | Thurs |                                |                                      |            |
| 02/18 | Mon   |                                | Ch.3                                 | A06        |
| 02/19 | Tues  |                                |                                      |            |
| 02/21 | Thurs |                                |                                      |            |
| 02/25 | Mon   |                                | Ch.4                                 | A07        |
| 02/26 | Tues  |                                |                                      |            |
| 02/28 | Thurs |                                |                                      |            |
| 03/04 | Mon   |                                |                                      | A08        |
| 03/05 | Tues  | Midterm Review                 |                                      |            |
| 03/07 | Thurs | Midterm - normal class time    |                                      |            |
| 03/11 | Mon   | Spring Break                   |                                      |            |
| 03/12 | Tues  | Spring Break                   |                                      |            |
| 03/14 | Thurs | Spring Break                   |                                      |            |
| 03/18 | Mon   |                                | Ch.5                                 | A09        |
| 03/19 | Tues  |                                |                                      |            |
| 03/21 | Thurs |                                |                                      |            |
| 03/25 | Mon   |                                | Ch.5                                 | A10        |
| 03/26 | Tues  |                                |                                      |            |
| 03/28 | Thurs |                                |                                      |            |
| 04/01 | Mon   |                                | Ch.6                                 | A11        |
| 04/02 | Tues  |                                |                                      |            |
| 04/04 | Thurs |                                |                                      |            |
| 04/08 | Mon   |                                | Ch.6                                 | A12        |
| 04/09 | Tues  |                                |                                      |            |
| 04/11 | Thurs |                                |                                      |            |
| 04/15 | Mon   |                                |                                      |            |
| 04/16 | Tues  |                                |                                      |            |
| 04/18 | Thurs |                                |                                      |            |
| 04/22 | Mon   |                                |                                      |            |
| 04/23 | Tues  | Final Review                   | None                                 | None       |
| 04/25 | Thurs | Final Exam - normal class time | None                                 | None       |
| 04/29 | Mon   | Finals Week                    |                                      |            |
| 04/30 | Tues  | Finals Week                    |                                      |            |
| 05/02 | Thurs | Finals Week                    |                                      |            |
| 05/06 | Mon   |                                |                                      |            |
| 05/07 | Tues  |                                |                                      |            |
| 05/09 | Thurs | Semester Ends                  |                                      |            |

[cli]: https://beebom.com/essential-linux-commands/
[pyth]: https://docs.python.org/3/library/functions.html#int
[m1]: http://docs.myhdl.org/en/stable/manual/preface.html
[m2]: http://docs.myhdl.org/en/stable/manual/background.html
[m3]: http://docs.myhdl.org/en/stable/manual/intro.html