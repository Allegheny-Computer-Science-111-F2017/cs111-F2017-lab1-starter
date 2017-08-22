# cs111-F2017-lab1

Designed for use with [GitHub Classroom](https://classroom.github.com/), this
repository contains the solution for Laboratory 1 in Computer Science 111.

## Introduction

This assignment requires a programmer to implement and test a Java program,
called `DisplayOutput`, that will produce four lines of output. The first line
of output will contain the name of the programmer and the date at which the
program was run. The next three lines of output will feature any one-sentence
and one-line statements of advice that the programmer would like to provide to
the person using the program. As verified by
[Checkstyle](https://github.com/checkstyle/checkstyle), the source code for the
`DisplayOutput.java` file must adhere to all of the requirements in the [Google
Java Style Guide](https://google.github.io/styleguide/javaguide.html).

The programmer is also responsible for writing a one-paragraph reflection,
stored in the file `writing/reflection.md`, that explains the challenges that
you faced and the solutions you developed. This is a Markdown file that must
adhere to the standards described in the [Markdown Syntax
Guide](https://guides.github.com/features/mastering-markdown/). Remember, you
can preview the contents of a comitted Markdown file by clicking on the name
of the file in your GitHub repository. Finally, don't forget that your
`writing/reflection.md` file should adhere to the Markdown standards established
by the [Markdown linting tool](https://github.com/markdownlint/markdownlint) and
the writing standards set by the [Proselint tool](http://proselint.com/).

The source code in the `DisplayOutput.java` file must also pass additional tests
set by the [GatorGrader tool](https://github.com/gkapfham/gatorgrader). For
instance, GatorGrader will check to ensure that `DisplayOutput` produces exactly
four lines of output and that you use the `new Date()` construct in the Java
code. When you use the `git commit` command to transfer your source code to your
GitHub repository, [Travis CI](https://travis-ci.com/) will initialize a build
of your assignment, checking to see if it meets all of the requirements. If both
your source code and writing meet all of the established requirements, then you
will see a green &#x2714; in the listing of commits in GitHub. If your
submission does not meet the requirements, a red &#x2717; will appear instead.
The instructor will reduce a programmer's grade for this assignment if the red
&#x2717; appears on the last commit in GitHub immediately before the
assignment's due date.

Available in the `assignment/` directory, the carefully formatted PDF assignment
sheet for this project provides more details about the steps that a programmer
should take to complete this assignment. You can also view this same PDF of the
assignment sheet by visiting the listing of laboratories on the course web site.

## Learning

If you have not done so already, please read all of the relevant [GitHub
Guides](https://guides.github.com/) that explain how to use many of the features
that GitHub provides. In particular, please make sure that you have read the
following GitHub guides: [Mastering
Markdown](https://guides.github.com/features/mastering-markdown/), [Hello
World](https://guides.github.com/activities/hello-world/), and [Documenting Your
Projects on GitHub](https://guides.github.com/features/wikis/). Each of these
guides will help you to understand how to use both [GitHub](http://github.com) and
[GitHub Classroom](https://classroom.github.com/).

To do well on this assignment, you should also read Chapters 1 and 2 in the
course textbook, paying particularly close attention to Sections 1.5 and 2.1.
Please see the course instructor or one of the teaching assistants or tutors if
you have questions any of these reading assignments.

## Commands

To get started in using the GatorGrader tool, you can change into the directory
for this assignment and type the command `./gatorgrader.sh --start` in your
terminal. Now, if you want to perform all of the checks that will automatically
evaluate your assignment, you can type the command `./gatorgrader.sh --check`.

Running this command will produce a lot of output that you should carefully
inspect. If the last line of the output indicates that GatorGrader judges that
there are no mistakes in the assignent, then this means that your source code
and writing are passing all of the automated checks. However, if the last line
of the output indicates that there are mistakes, then you will need to
understand what they are and then try to fix them.

You can also complete several important Java programming tasks by using the
`gradle` tool. For instance, you can compile (i.e., create bytecode from the
program's source code if it is a correct program) the program using the command
`gradle build`. There are also additional commands that you can type:

- `gradle clean`: clean the project of all the derived files
- `gradle check`: check the quality of the code using Checkstyle
- `gradle build`: create the bytecode from the Java source code
- `gradle run`: run the Java program in the command-line
- `gradle tasks`: display details about the Gradle system

To run one of these commands, you must be in the main directory for this
assignment where the `gradle.build` file is located. Then, you can type the
command in the terminal and study the output.

## Output

Typing the command `gradle run` in the terminal window produces the following
output for the instructor's version of `DisplayOutput`. As long as your program
adheres to all of the requirements for the assignment and passes all of the
verification checks, your version may produce (partially) different output.

```
> Task :run
Gregory M. Kapfhammer Tue Aug 15 21:49:19 EDT 2017
Hello world.
Gradle is great.
Travis is tremendous.


BUILD SUCCESSFUL in 0s
2 actionable tasks: 1 executed, 1 up-to-date
```

## Assistance

If you are having trouble completing any part of this project, please talk with
either the course instructor or a teaching assistant during the laboratory
session. Alternatively, you may ask questions in the Slack team for this course.
Finally, you can schedule a meeting during the course instructor's office hours.
