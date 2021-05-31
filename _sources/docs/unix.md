---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(launch/thebe)=
# Introduction to the Command Line

## What is it?
The command line is the text-based interface for the computer's operating system as a powerful alternative to the click-pointer interaction. It is a program that takes in commands and passes them on to the computer's operating system to run. For example, through the command line, you can create or delete files and edit their content. The advantage of using the command line is its power. You can run programs, write scripts to automate common tasks, and combine simple commands to handle difficult tasks. By the end of this session, you should be able to navigate, access, and modify files and folders on your computer - all without a mouse!

## Command Line Navigation 
When using the command line, we refer to folders as *directories*. Files and directories on your computer are organized into a *filesystem*. The *filesysstem* is the tree structure organization of the files and directorates in your computer. Think about it as the *Mac Finder* or *Windows Explorer* without the ability to access directories and files with a click. 

- The top directory in the filesystem is the *root* directory.

- In this nested structure, we refer to directories as *parents* and *childs* according to their position in the tree. The top directory is the *parent* of any other file or directory in the system.

```{code-cell} ipython3
%%bash
mkdir new-directory
```

