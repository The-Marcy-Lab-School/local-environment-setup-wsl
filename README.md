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

1. For the first part of this set up process, following the instructions in [this blog](https://medium.com/@fiqriismail/setup-wsl-on-windows-10-for-your-javascript-development-with-visual-studio-code-f63f75841e5f), except download **Ubuntu 22.04** instead of Ubunt 18.04. 

2. until your reach the "Creating the ReactJS application and test" section. You do not need to create a ReactJS application. 

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
 |-      etc...
```
You can do using the following commands:
* `cd` to navigate to the home directory.
* `mkdir Development` to create a folder for *all* your work.
* `cd Development` where you will create more subdirectories.
* `mkdir unit-5 unit-6 unit-7 unit-8` to make multiple folders at once.
* `ls` to ensure the folders were created.

![commands](./assets/commands.png)

3. If you ever want to view these files on your computer in File Explorer, run the command `explorer.exe .` in your terminal. File Explore will open your current working directory.

![fileexplorer](./assets/fileexplorer.png)

4. Next, you should type the command `code .` into your terminal and it will open VS Code for you. Remember this terminal command in the future. It will be very helpful!

5. Familiarize yourself with VS Code. This will be your new coding environment. It is very similar to AWS Cloud 9 as long as you **open VS Code via the Terminal** from the **home directory** (you can always navigate to the home directory with `cd` and no path following the command). 

6. Your directories and files are in the left panel. You can start a new "VS Code Terminal" by selecting Terminal from the top menu bar. The "VS Code Terminal" works *exactly* the same as your Mac "Terminal" and your "AWS Cloud9 Terminal"!

![vscode](./assets/vscode.png)

## Configure your Github using the Terminal

1. Follow these instructions to [set up Github in your terminal](https://github.com/The-Marcy-Lab-School/github-setup).  

## Confirm that everything is working

At this point, you should be able to clone down, work on, and push back up to Github all of your code. Test all of the following: 

1. Using the terminal, `git clone` one of your old Problem Sets that have tests. Make sure your keep your directory structure clean. You should clone it in an appropriate folder. You can always run `pwd` and `ls` to check where you are. 

2. In the terminal, `cd` into the problem set you just cloned down. Run `npm install`, then run `npm test` to see the tests run. 

3. Make a minor change to the `README.md` file of your problem set, add and commit that change, and push it back to Github. Double check using the Internet browser that your change was pushed to the remote repo. 


### If everything has worked as expected, reach out to an instructor for a final validation!
