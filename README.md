# Welcome to Introducing Git

THe components of this course have been derived or directly copied from [GitHub Campus Advisor training](https://github.com/github-campus-advisors/Campus-Advisor-Training) to provide a basic introduction to using Git.
The original course was solely designed for educators.

These materials have been updated to introduce using VS Code.
There are linked videos that may refer to Atom (that is now deprecated) although additional instructions are included in an effort to ensure that VS Code can be used as a drop in replacement.

While this course was designed for educators, the explanations and presentation of the concepts in the first two modules is suitable for anyone interested in getting started with Git and GitHub (or similar) repositories.

Modules 3 and 4 introduce GitHub Classroom and GitHub Education that are more appropriate for educators (using repository templates and GitHub Actions in GitHub Classroom can make for effective learning opportunities :wink:).

A further iteration of this course is likely to make it less tied to github.com; KCL users also have access to [github.kcl.ac.uk](https://github.kcl.ac.uk/).

If you find instances where things can be improved, then please create an issue in the original repository [here](https://github.com/kcl-eresearch/introducing-git/issues). If you are not familiar with issues in GitHub, no worries, you will learn about them soon.

## To Get Started

1. Register for an account on [github.com](https://github.com/).
2. [Download, install and configure VS Code](https://code.visualstudio.com/docs/setup/setup-overview#_set-up-vs-code-for-your-platform)

    #### Linux
    [VS Code on Linux](https://code.visualstudio.com/docs/setup/linux#_install-vs-code-on-linux)

    #### macOS
    [VS Code on macOS](https://code.visualstudio.com/docs/setup/mac#_install-vs-code-on-macos)

    #### Windows
    [VS Code on Windows](https://code.visualstudio.com/docs/setup/windows#_install-vs-code-on-windows)

3. [Download, install and configure git](https://git-scm.com/downloads).
    - If offered a selection of editor to use during the installation, choose one you recognise and are comfortable using
    - For all other options the default settings are suitable for getting started

4. Open VS Code and open a terminal

    #### Linux and macOS
    - The default terminal application is suitable
    - Select Terminal from the View menu

    #### Windows
    - the default terminal application will be PowerShell
    - to follow the terminal commands demonstrated throughout this course (and generally work better with Git)
        - Press `Ctrl + Shift + P`
        - Type: `select default profile` and press enter (or click on the command)
        - Select "Git Bash" from the displayed options
    - Select Terminal from the View menu

5. In the terminal that appears at the bottom of the VS Code window; set Git with the name and email address you used in step 1 using the following commands:
```
$ git config --global user.name "FirstName LastName"
$ git config --global user.email "email@example.com"
```
This is important because Git uses this information when you work on a project.

6. Create a repository from this template by clicking on "Create a new repository"

![](https://github.com/kcl-eresearch/introducing-git/blob/main/assets/template_01.png)

If you are doing this as part of an e-Research course at KCL where you have been given access to a namespace; please use a Repository name in the format `introducing-git-FirstName-LastName`

Once the repository is copied; click on Module 1 and you will be presented with an overview and links to video lessons from the directories README.md file with associated markdown (.md) files with guidance for completing assignments.

<hr>

## Questions
If you are a KCL user and have any questions regarding setup or about any of the learning modules, please create an issue in the original repository [here](https://github.com/kcl-eresearch/introducing-git/issues) or contact [e-Research support](mailto:support@er.kcl.ac.uk?Subject=introducing-git) for assistance.
