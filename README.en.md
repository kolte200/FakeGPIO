# Small, fast and concise tutorial on how to install and use python

## Index
- [Vocabulary](https://github.com/reza0310/Tutorials/blob/python/README.en.md#vocabulary)
- [Good to know](https://github.com/reza0310/Tutorials/blob/python/README.en.md#good-to-know)
- [Tutorial](https://github.com/reza0310/Tutorials/blob/python/README.en.md#tutorial)
- [Last update](https://github.com/reza0310/Tutorials/blob/python/README.en.md#last-update)

## Vocabulary
IDLE: Python's Integrated DeveLopment Environment. Whereas a bunch of similar softwares uses the acronym "IDE", Python uses IDLE. Might be a reference to Eric Idle from the Monty Python.<br>
PIP: Is a package manager for Python. It is used to easily download and install open source packages from the PyPI (= Python Package Index) repository.

## Good to know
There is a bunch of ways to make and execute Python code. If you have your own, this tutorial might be useless for you but if not you will learn the simplest way to do so using IDLE and pip for installing new packages.

## Tutorial
1) Download Python from the [official website](https://www.python.org/downloads/).

<br><br><br>
2) Launch the installer. On the very first page, you will have two thing to do: first check the "Add Python [...] to PATH" to be able to use python and, moreover, pip from the command prompt in the future. Then be sure to click on the "Install now" button. It will be faster and make sure to install IDLE and pip, our tools for this tutorial, in the process.

![Image illustrating step 2](https://github.com/reza0310/Tutorials/blob/python/1.PNG) 

<br><br><br>
3) Then, you will be asked if you want to disable path length limit. This option may not change anything for most of us but it can prevent some problems like if the path to the python executable file is more than 260 characters long. So I advice you to proceed with it.

![Image illustrating step 3](https://github.com/reza0310/Tutorials/blob/python/2.PNG) 

<br><br><br>
4) Then, you can close the installer. 

![Image illustrating step 4](https://github.com/reza0310/Tutorials/blob/python/3.PNG)  

<br><br><br>
5) As you can see, some applications got installed but two are gonna interest us: Python and IDLE. 

![Image illustrating step 5](https://github.com/reza0310/Tutorials/blob/python/4.PNG)  

<br><br><br>
6) Now, you can download the python project you want to execute. To do so, go to the project's github page and click on the green "Code" button and then click "Download ZIP" and unzip the file. If the file contain multiple scripts, to know wich one to execute try to find an explanation in the docs and if there is no such explanation, try to execute a script called "main", "index" or something like that. For my demonstration, I used my own [random pixels project](https://github.com/reza0310/random_pixels).

<br><br><br>
7) To execute your newly acquired script with python, you can do so from the command prompt by typing "python \[absolute / relative path to your script]" (hard method) or just double-click on it but this last method will open you a command prompt wich will close whenever the script end or raise an error. To be able to see your script's results or problems and manipulate it easily, you're gonna need an IDE such as IDLE or Pycharm. To open a scipt with IDLE, just right-click it and select "Edit with IDLE".

![Image illustrating step 7](https://github.com/reza0310/Tutorials/blob/python/5.PNG)

<br><br><br>
8) To run the script, click on "Run" -> "Run Module" or just press F5.

![Image illustrating step 8](https://github.com/reza0310/Tutorials/blob/python/6.PNG)

<br><br><br>
9) If it doesn't work and raise an "ModuleNotFoundError", don't worry i'm gonna cover how to patch this. If it raise any other error, then the error comes from the script itself and/or his compatibility with your system and if you are learning from this tutorial, it is very unlikely you're gonna be able to do anything for it except opening an "issue" on the corresponding github page to help the project's developers to make it work on your system and yes, it is very usefull you don't waste your time by doing so just be sure to give any information you have wich might be usefull.

![Image illustrating step 9](https://github.com/reza0310/Tutorials/blob/python/7.PNG)

<br><br><br>
10) For any "ModuleNotFoundError", take the module name (wich is written at the end of the line), open a command prompt and type "pip install \[module name]" to install this module and make the error disappear. If the pip command fail, try replacing every point in your module's name with underscores and if it still fails, try searching how to install this one mofule on the web.

![Image illustrating step 10](https://github.com/reza0310/Tutorials/blob/python/8.PNG)

<br><br><br>
11) Finally, enjoy the result ;)

![Image illustrating step 11](https://github.com/reza0310/Tutorials/blob/python/9.PNG)

## Last update
Sunday 20th february 2022
