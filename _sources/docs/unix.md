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

This module is designed to introduce you to the basic commands and tools needed to run your first scientific computing application. We will start with basic commands to execute in a Unix Shell.

The command line is the text-based interface for the computer's operating system as a powerful alternative to the click-pointer interaction. It is a program that takes in commands and passes them on to the computer's operating system to run. For example, through the command line, you can create or delete files and edit their content. The advantage of using the command line is its power. You can run programs, write scripts to automate common tasks, and combine simple commands to handle difficult tasks. By the end of this session, you should be able to navigate, access, and modify files and folders on your computer - all without a mouse!

## Command Line Basics

In the terminal, the first thing you see is an **$** symbol. This is called a *shell prompt*, and whenever you see it, it means that the terminal or shell is ready to accepy a command. But what is a command? A *command* is a text-based instruction to the computer to perform a specific task. For example, one of the commands you will use on a daily basis is *ls*.

When you type *ls*, the command line looks at the directory you are in, and "lists" all the files and directories inside of it. You can try it now for yourself!

```{code-cell} ipython3
%%bash
ls
```

## Command Line Navigation 
When using the command line, we refer to folders as *directories*. Files and directories on your computer are organized into a *filesystem*. The *filesystem* is the tree structure organization of the files and directorates in your computer. Think about it as the *Mac Finder* or *Windows Explorer* without the ability to access directories and files with a click. 

- The top directory in the filesystem is the *root* directory.

- In this nested structure, we refer to directories as *parents* and *childs* according to their position in the tree. The top directory is the *parent* of any other file or directory in the system. We are now going to explore a few basic commands to navigate your computer's *filesystem*. 

The next command we are going to explore is *pwd*. It stands for *print working directory* and it indeed, outputs the name of the directory you are currently in.

```{code-cell} ipython3
%%bash
pwd
```
Our next command is *cd*, which stands for *change directory*.

```{code-cell} ipython3
%%bash
cd <folder-name>
```

*cd* also allows you to navigate deeper into the *filesystem* without having to use it twice. For example, if you want to access *Folder1* inside *FolderA*, you can type

```{code-cell} ipython3
%%bash
cd FolderA/Folder1/
```
A useful tip is to use the *tab* key to autocomplete the name of a given file or folder. It will probably won't work on the web browser environment but you can try it on your Unix terminal. Also, let's say you want to access *Folder2* inside *FolderA* while you are already on *Folder1*, you can go back one level by typyng ../

```{code-cell} ipython3
%%bash
cd ../Folder2/
```

##Editing the filesystem

You can create a directory by typing

```{code-cell} ipython3
%%bash
mkdir <your-name>
```
to create a file, you can simply do

```{code-cell} ipython3
%%bash
touch <filename>
```

```{code-cell} ipython3
%%bash
for i in a b c;
do
echo $i
done
```
