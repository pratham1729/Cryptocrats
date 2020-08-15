# Cryptocrats

Official website of Tech Club of AISV-6 

---

If you want to contribute to the official website of Cryptocrats, follow the steps:

## Fork

First of all, fork this repository using the top right button, marked as 'fork'. This will create a copy of this repository in your account.

## Clone

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal or git bash and run the following git command:

```bash
git clone https://github.com/[your-username]/Cryptocrats.git/
```

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```bash
cd Cryptocrats
```

Now create a new branch using `git checkout` command:

```bash
git checkout -b [name-of-new-branch]
```


- For example

```bash
git checkout -b devansh
```

## Make and Commit changes

Now make the changes you want to make for the website. Once you've made all the changes, open terminal or git bash and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```bash
git add .
```

Now commit those changes using the `git commit` command:

```bash
git commit -m "[your-name] made changes"
```

## Push changes to github

Push your changes using the command `git push`:

```bash
git push origin <you-branch-name>
```

- For example

```bash
git push origin devansh
```

## Submit your changes

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon I'll be seeing the changes and if I think they're needed, I'll merge these changes to the master branch. You will recieve an email notification once the pull request has been merged.
