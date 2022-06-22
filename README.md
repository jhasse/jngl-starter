# JNGL Example Project

Starts a JNGL Game without any logic and just renders a black screen.

## Getting Started

Clone this folder and open it in VS Code. If it's the first time you develop C++/JNGL you have to install the dependencies documented in the JNGL [GitHub page](https://github.com/jhasse/jngl).
After setting up everything you only have to press F5 and the project will be built and started.

Happy developing!


## Windows Development with Visual Studio

For development on Windows you need to install:
- [Visual Studio](https://visualstudio.microsoft.com/de/downloads/)
- [CMake](https://cmake.org/download/)
- [Git](https://git-scm.com/downloads)
- optional [GitHub Desktop](https://desktop.github.com/)

Steps to build your first JNGL Game:

- Press the "Use this Template" Button and create your own repo.
- Clone the new repository with GitHub Desktop or on the console with `git clone --recurse-submodules`.
- Then open a console in your local project folder and run `cmake -Bbuild -DFETCHCONTENT_QUIET=0`, it will take a while and create a `build` folder.
- In the `build` folder there is now a `jnglexample.sln` which you can open with Visual Studio.
- In the solution explorer in Visual Studio you have to right click `jnglexample` and select `Set as Startup Project`.
- Now you can press Debug or <kbd>F5</kbd> to run your project.
- Have fun
