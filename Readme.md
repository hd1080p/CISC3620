# Lab 1: Open window

## Summary
The startup code for this class is cloned from (http://polytonic.github.io/Glitter/). It is intended to get you started with OpenGL by compiling and statically linking every required library, so you don't have to deal with all that. 

## Getting started
1. Clone the repository

   This repository has been created for you by GitHub Classrom. It exists as a *remote* repository. Visit [this page] (https://help.github.com/articles/cloning-a-repository/) for instructions on how to **clone** a repository to create a *local* copy on your computer. You will make changes to the code on your own computer and sync between the local and remote copies.

   *Note:* In step 6 of the instructions at the link, pass the `--recursive' flag to the clone command to generate all the dependencies:

   ```git clone --recursive https://github.com/YOUR-USERNAME/YOUR-REPOSITORY````

   Since you will be creating multiple repositories for this class, you may want to organize them in a directory structure such as cisc3620/labs/.

2. Generate a project file or makefile for your platform.

   If you don't have cmake installed on your machine, get it from (http://www.cmake.org/download/).

   Navigate to the Build subdirectory (one down from the top of the repository).

   Choose the appropriate command for your platform and IDE:

   ```bash
   # UNIX Makefile
   cmake ..
   
   # Mac OSX
   cmake -G "Xcode" ..
   
   # Microsoft Windows
   cmake -G "Visual Studio 14" ..
   cmake -G "Visual Studio 14 Win64" ..
   ```

3. Compile and run.

   You should see a window with a gray background.

## Modify

Open main.cpp for editing. The only change you need to make for this assignment is to change the background color (the clear color) from gray to blue.

## Submit
We will use the [fork and pull request](https://guides.github.com/activities/forking/)  workflow for submissions for this class. Follow the link for a guide to this workflow. The idea is that you will make the required changes in your own copy, and then submit a pull request and @mention me (@rivlev). __The pull request and @mention comprise your submission for this assignment.__ For this assignment, I will only look at the changes you make to main.cpp

This setup for this class is new, so please submit a separate pull request if you can clear up any errors or lack of clarity here. 

