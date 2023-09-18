# Getting Started with Git

Welcome to the world of Git! This guide will take you step by step through Git's foundational commands.

***NOTE***: Ensure you have `git` already installed. If not, please see [git setup here](../00_setting_up_your_environment/git). For Windows users, we recommend using Git Bash to run the code snippets.

## Setting Up Your First Git Repository

Think of Git as your automated change monitor for your code. Once initialised, Git will keep an eye on any changes you make. When you're ready, you can 'save' or 'commit' these changes.

To start, navigate to your project's directory in the terminal and type:

```bash
git init
```

Voilà! Your first Git repository is set up.

## Making and Tracking Changes

Let's create a text file in the root folder of your Git directory. Name it something like `filename.txt`.

### Git status

Want to see what Git thinks of your changes? Use `git status`:

```bash
git status
```

Output:

``` text
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        filename.txt

nothing added to commit but untracked files present (use "git add" to track)
```

This output tells you that `filename.txt` is an 'untracked' file. Think of a commit as a finalised document containing multiple sections of work. You keep adding to the commit until you're ready to finalise it.

### 1. `git add`

This command tells Git to track changes in specific files:

```bash
git add filename.txt
```

Or, to track changes in all files:

```bash
git add .
```

### 2. `git status` (again)

Check the status after adding:

```bash
git status
```

Output:

``` text
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   filename.txt
```

Now, Git recognises `filename.txt` as a file that's staged and ready to be committed.

### 3. `git commit`

Save a snapshot of your changes:

```bash
git commit -m "Added filename.txt as an example"
```

**Heads Up**: If you forget the `-m` flag with `git commit`, Git might open an editor (often VIM). To exit:

- Press `Esc`
- Type `:q!`
- Press `Enter`

## Reviewing Your Changes

### `git log`

To see a history of your commits:

```bash
git log
```

You'll see a list of commits, each with its unique ID, the date, and your message.

## Wrapping Up

Congratulations! You've taken your first steps into the vast world of Git. As you delve deeper, you'll uncover more advanced features and workflows.

Just remember to keep your changes small and commit small working block of code regularly. Large commits can be frowned upon as they can be hard to review and even harder to roll back!

For now, celebrate your progress. You're on your way! 
