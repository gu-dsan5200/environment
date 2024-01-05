# Environment for ANLY503

This page explains best practices in setting your machine to do the work for this course. We will be using R, Python, Quarto, Tableau, D3.js, and more.

We have also created curated R and Python environments which have many of the packages we will be using throughout the semester. We may make updates over the course of the semester. 

Since every student has a different machine, it is best to use a common environment that we know works.

## Learn to love your terminal/shell

There is a large amount of work in Data Science that happens at the command line. Regardless of operating system, you have a terminal that allows you to execute commands on your machine via written commands.

[**Terminal resources based on operating system:**]{.underline}

- **Windows users:** you will be using [_Powershell_](https://learn.microsoft.com/en-us/powershell/scripting/learn/ps101/01-getting-started?view=powershell-7.3) as your terminal. Note that there are times when you need to run Powershell with elevated privileges.  
- **Mac users:** Macs have a built-in Terminal (the _Terminal_ application). Consider using [iTerm](https://www.iterm2.com/) as an alternate Terminal application. This is not required, but highly recommended.

- **Linux users:** Linux machines have a built-in terminal.

Learn to love your terminal/shell. You will be doing a lot here, including your git work. No more uploading via web to GitHub.

## macOS

### Pre-requisites

- Update your macOS
- You may want to delete existing installations of Python, R and other applications and start with a clean slate.

### Installation

- Open your terminal
- Install xcode-select (macOS's suite of developer tools): `xcode-select --install`. Even though there is a `git` version installed with xcode-select, you will want to install brew's version.
- Install [`brew`](https://brew.sh/), the missing package manager for macOS.
- Install [miniforge](https://conda-forge.org/miniforge/) Python distribution (select the one called **Miniforge3**.)
- Use `brew` to install several items, including many popular tools/applications. Some of these are required for R or Python pacakges to be installed. Brew may install additional things (dependencies) and may request your username and password (and it's OK to provide):
	- [git](https://git-scm.com/): `brew install git`
	- [R](https://cran.r-project.org/): `brew install homebrew/cask/r` (Although you can run `brew install r` it is better to install the "cask". The "cask" is the pre-built application, while the `r` version needs compilation. If you install the plain `r` version you will need to compile most libraries.)
	- [RStudio](https://posit.co/products/open-source/rstudio/): `brew install rstudio`
	- [VSCode](https://code.visualstudio.com/): `brew install visual-studio-code`
	- [Quarto](https://quarto.org/): `brew install quarto`
	- [iTerm2](https://iterm2.com/): `brew install iterm2`
	- [GDAL](https://gdal.org/): `brew install gdal` (This is a pre-requisite for many of the geospatial libraries for R, on MacOS/Linux)
	- [PROJ](https://proj.org/en/9.3/): `brew install proj` (This is a pre-requisite needed for many of the geospatial libraries in R, on MacOS/Linux)
	- [Wget](https://www.gnu.org/software/wget/): `brew install wget`



- Download the course's Python environment file
- Download the course
- Optional: 



## Windows

There is a fairly new open source project called [Chocolatey](https://chocolatey.org/), which is analogous to macOS's `brew` but designed for Windows. There is a community that maintains the repository and creates the `choco` commands. The nice thing is that instead of having to go to websites and click download for applications, you can just install them via a single command.

### Pre-requisites

- Update Windows
- You may want to delete existing installations of Python, R and other applications and start with a clean slate.
- [Make sure you have Powershell available.](https://learn.microsoft.com/en-us/powershell/scripting/learn/ps101/01-getting-started?view=powershell-7.3)


### Installation instructions 

Note: you need to start Powershell with elevated privileges any time you want to install anything

- Open Powershell with elevated privileges
- [Install Chocolatey](https://chocolatey.org/install)
- Close and reopen Powershell with elevated privileges
- Use `choco` to install several applications:
	- [git](https://git-scm.com/): `choco install git`
	- [R](https://cran.r-project.org/): `choco install r` 
	- [RStudio](https://posit.co/products/open-source/rstudio/): `choco install r.studio`
	- [VSCode](https://code.visualstudio.com/): `choco install vscode`
	- [Quarto](https://quarto.org/): `choco install quarto`
	- [Miniforge](): `choco install miniforge3`
	- [Activate conda in Powershell](https://9to5answer.com/how-to-activate-conda-environment-from-powershell)




## Visual Studio Code



- Python (installs a few additional extensions supporting Python, Jupyter and more)
Jupyter
- Quarto
- R
- R Tools


