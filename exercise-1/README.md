# Exercise-1

The purpose of this exercise is to practice the steps you'll need to
use in future exercises. We'll begin by configuring your GitHub
account for your machine (which you'll only need to do once), and then
move through the steps of working with Git and GitHub (which will soon
become second nature).

1. If you haven't already, configure your name and email address for
your GitHub account using the terminal.  See [Installation &
Setup](https://faculty.washington.edu/otoomet/info201-book/git-basics.html#installation-setup). 

  ```bash
  # Set your name
  git config --global user.name "YOUR NAME"

  # Set GitHub email - make sure it matches your account online
  git config --global user.email "YOUR EMAIL"
  ```

2. Fork this repository (`ch4-git-basics`) to your own GitHub account
by clicking the `fork` button on the GitHub interface.  See [Forking
and
Cloning](https://faculty.washington.edu/otoomet/info201-book/git-basics.html#forking-and-cloning).

  ```bash
  #  Click the `fork` button to fork it to your account
  ```

3. Using your terminal, clone **your forked repository** to your
machine (make sure you're in the desired directory on your terminal)

  ```bash
  # Enter a desired directory
  cd ~/Documents

  #  Get the URL by clicking the "Clone or Download" button on GitHub, then clicking the clipboard icon

  # Clone the repository
  # You find the exercise URL by clicking on the green 'Code' button on Github
  git clone <exercise url>

  # go to the cloned repository
  cd ch04-git-basics/exercise-1
  ```
  

4. On your machine, open up this file (`exercise-1/README.md`) in a
text editor of your choice.  RStudio is good, Atom is good, there are
many good editors for markdown.

  ```bash
  # Open up the file
  ```

6. Using your terminal, add and commit the changes you've made to your
   repository.  See [Making
   Changes](https://faculty.washington.edu/otoomet/info201-book/git-basics.html#making-changes). 

  ```
  1. Coffee
  2. Banana
  3. Cheerios
  ```

In terminal you need to issue command along these lines:

  ```bash
  # Make sure that you're in the cloned repository
  pwd

  # Commit changes making sure to include a descriptive message
  git commit -am "DESCRIPTIVE MESSAGE HERE"
  ```

7. Push changes up to GitHub.  See [Pushing and
   Pulling](https://faculty.washington.edu/otoomet/info201-book/git-basics.html#pushing-and-pulling). 

  ```bash
  # Push changes
  git push
  ```
