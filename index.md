# Lab Report 4 

---
# Step 4: 

First step we need to complete is to `ssh` to gain remote access and then `git clone` the given respository.
- Keys pressed: `ssh` jopak@ieng6.ucsd.edu `<enter>`
  Initiates an SSH connection to the ieng6 server, allowing remote access.
- When prompted `<enter>` password 

<img width="682" alt="x1" src="https://github.com/jpak0/labrepo4/assets/48459170/14816d1e-e628-409d-8bb7-e875358fcd73">


# Step 5 
 
Using `<ctrl><r>` I was able to referenced my  history, specifically commands made in the lab that allowed for this shortcut to be made. I then entered `gi` in the reverse search and the clone with the selected repository showed up.

Cloning my forked repository from my GitHub, I used the following:

- Keys pressed: `<ctrl><r>` `gi<tab>` `<enter>`
- Keys pressed if no history: `git clone` `<enter>` "repository"
  Uses Ctrl+R to search the command history, types `gi,` and uses tab completion to select the` git clone` command for the repository. Then, executes the command to clone the repository to the local machine.

<img width="682" alt="Screenshot 2024-03-12 at 11 20 32 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/b075bd72-ad2c-4a63-90b3-c8db549844ae">

Once cloned, I pressed `<Enter>`
- Keys pressed: `<Enter>`
  Executes the `git clone` command and clones the repository to the local machine.
<img width="682" alt="Screenshot 2024-03-12 at 11 22 07 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/5176fd86-fc37-4d25-b825-95fdb741a3cf">


With `ls` I could see lab 7 listed. Then with past knowledge of how to do so, I changed the directory to lab 7 with the commmand;`cd l<tab>` this allowed for me to practice professors shortcut using `<tab>`
- Keys pressed: `ls``<enter>`
  Lists the contents of the current directory.
- Keys pressed: `cd l<tab>``<enter>`
  Will make the directory to "lab 7" using tab completion.
<img width="682" alt="Screenshot 2024-03-12 at 11 23 18 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/b8bea82b-48d4-431a-9aef-08714a7287c8">


# Step 6

With `ls`, I found a file named `test.sh`. To check the contents of the bash script using the `less` command, I used the following keystrokes:

- Keys pressed: `less te<tab>``<enter>`
  Uses the less command to view the contents of the `test.sh` file.
<img width="682" alt="Screenshot 2024-03-12 at 11 24 11 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/1e303b4e-0fae-4ad9-ae4e-6664545e1bb7">


Pressing `Q` allowed me to return back.

To run the tests and observe the failures, I executed the following command:

- Keys pressed: `bash te<tab>``<enter>`
  Runs the tests by executing the `test.sh` bash script.

Running `bash tesh.sh` gives us the failed tests and the exact line where the error is.
<img width="682" alt="Screenshot 2024-03-12 at 11 24 40 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/948e0bc8-b0f7-4c22-abc9-c454edf00aa5">


# Step 7

I went back to the problematic file called `ListExamples.java` using the command `vim ListExamples.java` showing and allowing us access to all the lines located in that file.

To access the problematic file, `ListExamples.java` and edit it using the vim editor, I used the following keystrokes:

- Keys pressed: `vim ListExamples.java` `<enter>`
  Opens the `ListExamples.java` file in the vim editor, allowing access to all the lines in the file.
<img width="682" alt="Screenshot 2024-03-12 at 11 25 52 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/45ddd8c7-d8a5-48a4-ab16-bb5e6c358783">


In the vim, To enter insert mode and make changes, I pressed `I`.
In insert, I found the error at line 44. I pressed the `<down>` key to navigate down until I reached the error.
I changed "Index1" to "Index2" to fix the error.
Once the changes were made, I exited INSERT mode by pressing `<Escape>`. To exit vim and save the changes, I used the keystrokes `<Shift><;><W><Q>`.

 <img width="682" alt="Screenshot 2024-03-12 at 11 27 21 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/ef0c382e-66e5-4b30-a578-574c3d233791">


- Keys pressed: `ls`, `less ListE<tab>``<enter>`
  Uses `ls` to list the contents of the current directory, then uses `less` to view the contents of the `ListExamples.java` file.

# Step 8

Test run again,we press `bash test.sh` then `<enter>`.

- Keys pressed: `<up>``<up>``<up>``<up>``<enter>`
  Uses the up arrow key to access the previous command from the command history. This retrieves the `bash test.sh` command from Step 6, allowing for easy re-execution of the test script.

<img width="492" alt="Screenshot 2024-03-12 at 11 37 31 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/a560047d-934d-467c-a717-14351b6c1d81">


# Step 9

The final step involves committing the code to GitHub. Here are the necessary keystrokes:

- Keys pressed:  `git push<enter>`
 git pushes the changes to the GitHub repository using `git push`
 Once found, executes the command to push the committed changes to the GitHub repository.

<img width="561" alt="Screenshot 2024-03-12 at 11 54 59 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/7740a017-5bf7-4b4b-8902-8cb860a2571f">
<img width="587" alt="Screenshot 2024-03-12 at 11 54 44 PM" src="https://github.com/jpak0/labrepo4/assets/48459170/c1633909-10c1-4dbe-9134-b6c08961caf9">
