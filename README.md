# ScrivenerTemplates
Various Scrivener templates preconfigured to better integrate with Git.

## Details
The default Scrivener templates were modified to add various .`gitignore` and `.gitkeep` files in strategic places to make syncing with Git easier.

Specifically, `.gitignore` files were added to the root directories of the project templates, and `.gitkeep` files were added to the project templates' *Settings* and *Files/Docs* directories.

The templates used were taken and modified from **Scrivener for Linux v.1.9.0.1** so they should be compatible with the equivalent Windows and Mac versions or greater (after auto-conversion upon open).

## How To Use
1. *Copy* the .scriv project folder that you wish to use to your working Git project folder (and optionally rename it to anything you like).
2. Open that project folder in Scrivener.
3. Use Scrivener to make your changes.
4. When done, *Save* the project in Scrivener, run `git add .` to add any changes that were made to the project folder, use `git -m` to add your commit message, optionally use `git tag` to tag your commits, and finally use `git push` to sync your changes.

