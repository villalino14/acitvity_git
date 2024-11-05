## Get the Repository URL:

Go to the repository on GitHub.
Copy the repository's URL (usually found in the "Code" button).

## Clone the Repository:

Open your terminal or command prompt.
Use the `git clone` command, followed by the repository URL

```bash
git clone <repository-url>
```

Replace <repository-url> with the URL you copied.

## Navigate into the Repository:

After cloning, move into the new directory created by the clone command

```bash
cd <repository-name>
```

Replace <repository-name> with the name of the folder created during cloning (usually the name of the repository).

## To create a new branch in an existing repository, you can use the Git command line or a Git GUI tool. Here’s how to do it with Git commands:

## Open Terminal or Command Prompt:

Navigate to the repository's directory if you haven't already.
List Current Branches (optional):

```bash
git branch
```

## Create a New Branch:

```bash
git branch branch-name
```

Replace `your Surname` with the desired name of your new branch.

## Switch to the New Branch:

```bash
git checkout branch-name
```

## Push the New Branch to the Remote Repository (if needed):

```bash
git push -u origin branch-name
```

This sets up tracking between your local branch and the remote branch.
