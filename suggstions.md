## Suggestions
Hope you don't mind! I put together a list of things I've done as a developer and I think would be useful to learn!

Create an organization for the class, and add all students as developers. Basically, all students need to be able to **create**, **clone**, **branch** from, **push** to, and **make pull requests** for repositories.

### Stuff to do
_____
- Using the git CLI & using Github to initialize a repository within the organization on github
	- Do not initialize w/ a `README.md`, but make it yourself and setup the origin from the cli.
	- Create a small program in a language of your choice. Make it extremely simple. Anything you want, really. What is important is that **it works**, and there are **simple instructions** on how to run it. *Personally, I suggest a simple node program, as the `package.json` allows for easy install and run of the program.*
	- Use clear and concise commit messages. **More than one commit**

- The Clone Wars
	- Install and run the code. Whatever the program is, it should work according to it's instructions.
	- Star the repo so you get updates

- Stop, **collaborate** and listen
	- Create a branch in your classmate's repo
	- Add a new small feature to the program, *but leave an intentional bug within the changes*. It must be simple enough
	- add your changes to your staging with `git add -p` (shows each block, very useful)
	- commit and push the branch, and then create Pull Request on Github
	- explain your changes in the body of the PR if you feel the need
	- When you receive the PR (if a student hasn't gotten one from another student by a certain date, Trevor can do it or something), review the changes to the code in the PR
	- **the PR should contain a bug of some kind. Find it, and leave a comment calling it out**
	- the classmate responsible for the PR should then fix the bug and push again to fix the PR
	- the classmate owning the repo can then review again and merge the request. Pull the changes locally, and run the code. It should work, with the new feature added by a classmate
- Optional:
  - tag a version
  - rename a branch
  - git stash / git pop
  - using the cli to merge changes into your own branch
  - conflicts, and how to resolve them
  - discuss the permanence of commits, and the effort required to actually scrub something from git history
  - `.gitignore` and `.gitkeep` files
  - checking out older commits
  - forkings vs branching
