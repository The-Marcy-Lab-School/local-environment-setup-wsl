# Local Environment Setup: Windows

Today, we'll be setting up our local development environment for Windows 10. For the Mac instructions, see [here](https://github.com/The-Marcy-Lab-School/local-environment-setup-mac). 

## Table of Contents
0. Set up Windows Subsystem for Linux (WSL)
1. Download VS Code for Windows and command line tools
2. Install Node and NPM 
3. Set up local Development directory
4. Configuring Github with your Terminal
5. Add SSH Key for Github Setup

### Enable WSL and Download VS Code, Node, NPM

1. For the first part of this set up process, following the instructions in [this blog](https://medium.com/@fiqriismail/setup-wsl-on-windows-10-for-your-javascript-development-with-visual-studio-code-f63f75841e5f) until your reach the "Creating the ReactJS application and test" section. You do not need to create a ReactJS application. 

2. You should now have WSL installed, VS Code **for Windows** installed, and Node installed.

3. You should pin Ubuntu Terminal and VS Code to the taskbar since you'll be using them a lot. 

![taskbar](./assets/taskbar.png)

4. From now on, we'll refer to your Ubuntu Terminal as just **Terminal**.

## Set up local Development directory

1. Every time you open your Terminal, you'll be in the home directory. Run `pwd` to see the current path. You'll see `home/your-user-name`.

![home](./assets/home.png)

2. Using your Terminal as a command line, create a folder structure where you can put all your Marcy Lab code. We recommend:
```
Development
 |- unit-5
 |- unit-6
 |- unit-7
 |- unit-8
```
You can do using the following commands:
* `cd` to navigate to the home directory.
* `mkdir Development` to create a folder for *all* your work.
* `cd Development` where you will create more subdirectories.
* `mkdir unit-5 unit-6 unit-7 unit-8` to make four folders at once.
* `ls` to ensure the folders were created.

![commands](./assets/commands.png)

3. If you ever want to view these files on your computer in File Explorer, run the command `explore.exe .` in your terminal. File Explore will open your current working directory.

![fileexplorer](./assets/fileexplorer.png)


- Type `code .`
- Tell your firewall to allow access

Summary of useful command line
- `clear`
- `explorer.exe .`
- `code .`