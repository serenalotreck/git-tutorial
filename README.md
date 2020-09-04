# git-tutorial
Toy repo for teaching how to use git/GitHub

## Instructions 
### Part 1: Basic usage 
1. Clone this repo! `git clone <URL>`
2. Make a new file in the repo called `<yourName>.py`. Put some simple function of your choice (for example, you could make a function that prints the sentence 'Hello world!'). Save, add, commit, and push this file.
3. Since there are several of us, if you're not the first to commit, you may get a message from git saying that you need to pull before you can push. If this happens, use `git pull`, and then you'll be prompted to enter a merge message. Something like "Merge X with Y" should suffice here.
### Part 2: Merge conflicts
1. Use `git pull` to get the most recent version of the repository. 
2. The file `hello_world.py` contains a docstring. In the docstring, delete the line that says "Change this line!" and replace it with whatever you want.
3. Under the line "My name is Serena and I like ice cream", add another line with your name and something about yourself.
4. Save, add, commit, and try and push; I'm hoping this will create a nice messy merge conflict that we have to work through together!
