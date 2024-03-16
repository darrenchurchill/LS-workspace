# Launch School VS Code Workspace Config

Although all my local repositories share a single root directory, I’ve preferred
to use VS Code’s [multi-root workspace](https://code.visualstudio.com/docs/editor/workspaces#_multiroot-workspaces)
option to individually add new repositories to the workspace as needed.

Therefore, this repository tracks a single file: `launchschool.code-workspace`.
This repository should be cloned as a sibling to all the other school-related
repositories. You can see this in the relative paths in
`launchschool.code-workspace`.

## Opening the Workspace

You can open a multi-root workspace with the "File > Open Workspace from File"
menu option, or by running:

```console
code launchschool.code-workspace
```
