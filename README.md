# sublime-settings

Personal settings for Sublime Text 3

1. Click `Preferences / Browse Packages...` to find path to SublimeText packages.
2. Open a terminal and change to the same directory.
3. Run `git clone https://github.com/jongiddy/sublime-settings.git`.
4. Copy the contents of directory `sublime-settings` to directory `User`.
5. Add Package Control, using the instructions at <https://packagecontrol.io/installation>
6. Add the following packages by `Ctrl`-`Shift`-`P` `Package Control: Install Package`

## Installed Packages

### Top Priority

- Anaconda
- OmniMarkupPreviewer
- RestructuredText Improved
- SideBarEnhancements
- VCS Gutter

### Lower Priority

- Better CoffeeScript
- Floobits
- SideBarGit

## Other Actions

For SideBarGit, ensure `git` and `gitk` are in `PATH`.
Restart Sublime Text to ensure it can see the new PATH.

Install `pandoc` from <http://johnmacfarlane.net/pandoc/installing.html>
