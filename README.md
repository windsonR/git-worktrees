# deprecated
`Visual Studio Code@1.108` experimental support git worktree's manage and new.

After `VSCode's` git plugin supports worktree, this plugin is no longer necessary (at least in my opinion).

# vscode

Set `scm.repositories.explorer` to `true` and `scm.repositories.selectionMode` to `'single'`

# about

This repo forked `https://github.com/joaorr3/git-worktrees`.
And it changed a little to use.

# changed

- worktree will always open in new window.
- when create a new worktree, it will always use the same `.worktree` folder, like this:

```
- a
  - .git
- a.worktree
  - a.branchA
    - .git
  - a.branchB
    - .git
- b
```

# git-worktrees-explorer

This extension provides a GUI for managing git worktrees. You can add, delete and switch between them.

## Features

- Add a new worktree by creating a new branch or from selection an existing one.
- A new directory will be created for you based on the current branch path. For ex. Your repo is called `MyAwesomeRepo` and you've added a new worktree from a branch called `MyAwesomeBranch`. A new directory called `MyAwesomeRepo.worktrees` will be created with a folder `MyAwesomeBranch` inside it.

## Add

![add-with-branch](https://user-images.githubusercontent.com/38807975/179556026-d9bc6cab-6a90-4f89-8ca9-6dd662815e4d.gif)

![add-from-existing](https://user-images.githubusercontent.com/38807975/179556101-ed2c704e-9a92-4b68-8119-f877b673d0e1.gif)

## Remove

![delete](https://user-images.githubusercontent.com/38807975/179556182-3bd139dd-da33-4a80-9267-9d8dbee6b766.gif)

**Enjoy! ❤️**
