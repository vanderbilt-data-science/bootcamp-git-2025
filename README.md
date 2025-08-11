# DSI Bootcamp 2025 Git Workshop
A repo for practicing your git skills as an incoming MS student at the DSI

## Introductions

(see instructions)

**Name:**

**Hobbies:**

## Section 1: Your First Commit

1. Fork this Repo
   - In the top right corner of GitHub, you should see an option to **fork** this repository.

2. Clone the Repo to your machine
  
3. Introduce yourself!
   - On your local repo, edit the "Introductions" section of the readme to add your **name** (ignore hobbies for now).

4. Make a commit and push your changes
   - Don't forget to add a helpful commmit message
  

## Section 2: Working in Pairs

Use one person's fork of this repo to complete the following.

Partner A: use your repo
Partner B: use Partner A's repo


1. Partner A: add Partner B to your repo (under Settings)
2. Partner B: clone Partner A's repo to your machine
3.
   - Partner B: Add your name and hobbies to the README on your clone of Partner A's repo.
   - Partner A: Add your hobbies to the README on your local repo.
4. Everyone: Commit and push changes
   
This will result in a merge conflict! (Unless you waited for each person to make their changes before making yours.) 

Let's go over how to fix this!!!


## Section 3: GitHub Flow

Now that we have seen the horrors of merge conflicts, let's better manage this with GitHub Flow. This exercise will use the `shape_attributes.py` file.

**Goal:** The main task to be completed is to create a function compute_area in the `shape_attributes.py` file. The function computes and returns an area based on a radius r. For reference:

The area of a circle is 
π
r
2
The area of a sphere is 
4
π
r
2

### Merging via GitHub

Now both team members complete the assigned tasks using the following steps:

1. Create a new branch with an appropriate title git checkout -b <branch_name>
2. Make changes to your code in the new branch and save them
3. Add your changes to the staging area  `git add shape_attributes.py`
4. Commit your changes from the command line using `git commit -m "your message here"`
5. Push your changes to the remote branch using `git push -u origin <branch_name>` (fill in the actual name of your branch without the < > )
6. Create a pull request and assign it to your partner

Partner A reviews Partner B’s PR, merges, deletes branch, and closes the PR.

Partner B reviews Partner A’s PR, and UH OH! Conflict!! Partner B fixes it on GitHub. Merge, delete branch, and close the PR.

### Merging locally
You'll be repeating the same exact steps above to the existing repo, except for 1) the changes to be made to the file, and 2) the resolution of the merge conflict. For 1, we'll be adding a new line below the function with a comment about what the function does. For 2, instead of merging via GitHub, we'll use the most recent version of main and merge this into the relevant branch. The steps are repeated below.

Now both team members complete the assigned tasks using the following steps:

1. Create a new branch with an appropriate title git checkout -b <branch_name>
2. Make changes to your code in the new branch and save them
3. Add your changes to the staging area  git add shape_attributes.r
4. Commit your changes from the command line using git commit -m "your message here"
5. Push your changes to the remote branch using git push -u origin <branch_name>
6. Create a pull request and assign it to your partner.
   
Partner A reviews Partner B’s PR, merges, deletes branch, and closes the PR.

Partner B reviews Partner A’s PR, and UH OH! Conflict!! Partner B fixes it locally (via VSCode, R, etc). Merge, delete branch, and close the PR.
