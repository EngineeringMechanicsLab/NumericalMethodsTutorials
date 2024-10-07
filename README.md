# NumericalMethodsTutorials
A curation of tutorials for simulating physical systems by using numerical methods.


## The Basics
There are many existing references on getting started with using Python and coding. Below are some basic steps to follow as you get started.

1. **Python** Installation instructions for Python can be found on the [website](https://www.python.org/about/gettingstarted/).
    - **IDE** Using an Integrated Development Environment (IDE) will make coding easier. There are many IDE's available. I have found VS Code with the Python extension as a nice editor. Directions for installing VS Code, Python, the Python extension in VS Code, and running a basic script inside the IDE are available [here](https://code.visualstudio.com/docs/python/python-tutorial).
    - **Packages** There are many useful existing Python packages, which are searchable [here](https://pypi.org). While there are many, two to go ahead and add include:
        - numpy (for math equations and array computations)
        - matplotlib (for plotting)
2. **Git** Git is an version control management software that is used to keep track of codes as they undergo development. Additional details are on the [website](https://git-scm.com). You should download git if it is not already on your computer. 
    - Git is traditionally used as commands in the terminal. These are the commands that you will see in the [documentation](https://git-scm.com/doc). A nice walkthrough of basic git commands and using a git repository is available [here](https://antonz.org/git-by-example/). Many IDE's also contain helpful visual methods for using git, which can be more user-friendly for new coders. For example, VS Code has built in git support, with a tutorial available [here](https://code.visualstudio.com/docs/sourcecontrol/overview).


## Toy Problems
Here we curate a few 'toy problems'. These problems are simpler, with their purpose serving to provide a solvable system to develop your scientific computation skills to be used on future, potentially more complex problems of interest.
### 1. Euler-Bernoulli Beam
The general Euler-Bernoulli beam equation is
$$
\begin{equation}
EI\frac{\partial^4 W(x, t)}{\partial^4 x} + \mu \frac{\partial^2 W(x, t)}{\partial^2 t} = F(x, t)
\end{equation}
$$
where $W(x, t)$ is the displacement of the beam at point $x$ and time $t$, and the beam has a constant Young's modulus $E$ and area moment of inertia $I$ and mass per unit length $\mu$. Lastly, the beam is subjected to a force per unit length of $F(x, t)$.
To practice solving solid mechanics problems, solve for the steady state displacement of a beam with a known static loading scenario. Your numerical solution should be directly comparable with existing theory from statics/deforms textbooks.


## Helpful Textbooks
- R. C. Hibbeler, Mechanics of materials, 9th ed. Upper Saddle River, N.J: Prentice Hall, 2014.
    - Introductory textbook to deforms and mechanics of materials.
    - See chapter 12 for details on relating the loading on the beam and the resulting deflection of the beam.
- L. D. Landau and E. M. Lifshitz, Theory of elasticity, 2nd ed. in Course of theoretical physics / L. D. Landau and E. M. Lifshitz, no. 7. 1970.
    - Detailed theoretical treatment of solid mechanics.
- J. D. Anderson, Computational fluid dynamics: the basics with applications. in McGraw-Hill series in mechanical engineering. New York: McGraw-Hill, 1995.
    - A textbook on computational fluid dynamics.
- S. C. Chapra and R. P. Canale, Numerical methods for engineers, Seventh edition. New York, NY: McGraw-Hill Education, 2015.
    - Introductory textbook to numerical methods. While all parts are useful to know, parts 6-8 (chapters 21-32) are particularly relevant for our purposes.

## Additional Resources
- Completely new to programming? There are many references available. A small list has been curated on the Python [website](https://wiki.python.org/moin/IntroductoryBooks).
- Another online resource is available which has two parts: the first part on the basics of Python, and the second part on implementing some basic numerical methods using Python. The online textbook is called [Python Programming and Numerical Methods](https://pythonnumericalmethods.studentorg.berkeley.edu/notebooks/Index.html) by Qingkai Kong, Timmy Siauw, and Alexandre Bayen. 

## Potential Courses of Interest
Here, we have a list of already existing courses which cover different parts of numerical methods. These courses could be consulted for further structured study of numerical methods.
- [Introduction to Numerical Analysis](https://ocw.mit.edu/courses/18-330-introduction-to-numerical-analysis-spring-2012/pages/syllabus/). Undergraduate level.
- [Computational Methods of Scientific Programming](https://ocw.mit.edu/courses/12-010-computational-methods-of-scientific-programming-fall-2011/pages/syllabus/). Undergraduate level.
- [Essential Numerical Methods](https://ocw.mit.edu/courses/22-15-essential-numerical-methods-fall-2014/pages/syllabus/). Graduate level, emphasis on methods for nuclear engineering applications.
- [Introduction to Numerical Methods](https://ocw.mit.edu/courses/18-335j-introduction-to-numerical-methods-spring-2019/pages/syllabus/). Graduate level.
- [Numerical Methods for Engineers](https://www.coursera.org/learn/numerical-methods-engineers). Undergraduate level, MATLAB based.