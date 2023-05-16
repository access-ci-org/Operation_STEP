# Git Workshop: Creating and Cloning a Repository

## Helpful Shell Skills

- `cd` to change directory
- `pwd` to show the current working directory
- _Copying text out of your terminal, and pasting it in_
- Text editor (e.g. `nano`)

<!--
Let's take a minute to review these if anyone is unsure about them.
-->

## Exercise: Ensure Git is Installed

```shell
git help
```

(`help` accepts subcommands, e.g. `git clone --help`, but shows LOTS of detail)

---

## Exercise: Create a New Project From Scratch

```shell
mkdir your-project
cd your-project
git init
git status
```

---

## Exercise: Clone Someone's Existing Project

Perhaps you found something on GitHub, you want to use it or contribute to it.

```shell
cd
git clone https://github.com/access-ci-org/Operation_STEP.git
cd Operation_STEP
git status
```

**Vocabulary:** to _clone_ a Git repo means to download a copy from the internet.

---

## Exercise: Where is the Git Magic Stored?

Run this from the _root_ directory of a repo:

```shell
ls -a
```

`.git` directory contains all the metadata related to the history of the repo.

<!--
If you delete it, your directory ceases to be a Git repository!
-->