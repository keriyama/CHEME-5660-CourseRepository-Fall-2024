# Introduction
This course is for engineers and scientists interested in quantitative finance and consulting. It covers financial systems, markets, and the fundamental assets and tools in quantitative finance. Additionally, it includes modeling, analysis, and simulation of fixed-income securities, equity instruments, and derivative products. The course also explores portfolio optimization, hedging strategies, and the statistical properties of financial data. It concludes with advanced topics such as the application of artificial intelligence to decision-making, providing students with tools for pursuing entrepreneurial and quantitative finance employment opportunities.


HELLO DOES THIS WORK

For more information on the course content, policies, procedures, and schedule, see the [2024-2025 Courses of Study](https://classes.cornell.edu/browse/roster/FA24/class/CHEME/5660).

## Requirements
All of these items need to be installed on your machine to complete the assignments and projects in this course.

This course uses [the Julia programming language](https://julialang.org/downloads/) to introduce fundamental concepts of technical computing, data science, machine learning, and artificial intelligence. 
In addition, we use other tools and languages, such as [Python via the Anaconda distribution](https://www.anaconda.com) and [Jupyter Notebooks](https://jupyter.org), [GitHub Desktop](https://desktop.github.com/) for repository management, [GitHub classroom](https://classroom.github.com) for assignments. Finally, we use [Visual Studio Code (VSCode)](https://code.visualstudio.com/download) for development. 

### GitHub Desktop and Anaconda
* GitHub Desktop is a free, open-source application that allows you to work with code hosted on GitHub, such as this course repository. With GitHub Desktop, you can perform Git commands in a graphical user interface, such as committing and pushing changes, rather than using the command line. To download and install GitHub Desktop, follow the [instructions here](https://desktop.github.com/)
* Anaconda is a distribution of the Python and R programming languages for scientific computing that aims to simplify package management and deployment. To install Anaconda on your machine (if you don’t already have a working Python/Jupyter installation), follow the [instructions here](https://www.anaconda.com/download). 

### Julia
`Julia` is a high-level, general-purpose dynamic programming language for numerical analysis and computational science. To download and install the latest version of [Julia](https://julialang.org/downloads/), follow the [instructions here](https://julialang.org/downloads/) for your respective platform.
* For Windows users: Select the `add to path` option during installation to add `Julia` to your search path. You'll need this so that we can start [Julia](https://julialang.org/downloads/) from the terminal in [VSCode](https://code.visualstudio.com/download).
* For macOS users: follow the instructions on the [Julia website for updating the macOS path from the terminal](https://julialang.org/downloads/platform/#optional_add_julia_to_path).

Alternatively, macOS users can manually update your `.zshrc` file in your home directory to include the path entry (edit using Nano or some other text editor): 
```zsh
export PATH=“$PATH:/Applications/Julia-1.10.app/Contents/Resources/Julia/bin”
```

### Visual Studio Code (VSCode)
Visual Studio Code is a streamlined code editor that supports development operations such as debugging, task running, and version control. It is free and runs on all major platforms. 
To download and install VSCode, follow the instructions [here](https://code.visualstudio.com/download). Once VSCode is installed, add the Julia language extension via the extensions menu (open the extensions, search for Julia, and install the extension). 

### IJulia
The `IJulia` package must be installed globally so that Jupyter can use `Julia` as a kernel, i.e., we can write `Julia` code in Jupyter notebooks. To install the `IJulia` package, follow these steps:
1. Open the VSCode editor and start a new terminal by selecting the `New Terminal` option from the `Terminal` menu.
1. In the terminal window (zsh for macOS, and PowerShell for Windows) in VSCode, type the command: `julia`
2. Once `Julia` starts, enter package mode by typing the `]` key, and enter the command: `add IJulia`

