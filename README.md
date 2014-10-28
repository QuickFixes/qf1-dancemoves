# Dance Moves
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/QuickFixes/just-gittin-started)
### A Starter Project for QuickFix #1
![the walken of choice](assets/weaponofchoice_still.jpg)

## First steps
1. Use the GitHub web site to create a "fork" of this project
    * _Wait, but why can't I use the GUI?_
        * You can if you're a [member of the organization][h-perms] that hosts the repository, or if the person who owns the repository [adds you as a collaborator][h-collab].

    * _Wait, but what good is cloning if I can never make changes?_
        * Maybe you just want to _use_ the software. Plenty of software projects (particularly stuff like [text editor plugins](https://github.com/vim-scripts "Plugins for the Vim editor") and [web development frameworks](https://github.com/twbs/bootstrap#quick-start "Twitter Bootstrap")) use Git as a means of distributing their software. You just `git clone` the project into a particular directory and BAM! If you wanted to _contribute_ to these projects, you'd [make a fork][g-fork]).

2. _Now_ use the GitHub GUI to "clone" this repository to your laptop

## Activities

- [ ] Have a look at the revision history in the GitHub GUI
- [ ] Make a few simple changes of your own. Commit them. Use a good commit message.
- [ ]  Push those changes to "origin" (your github.uc.edu/github.com fork).
    * Look at the history and the "diffs" on GitHub.com and in the GUI client
- [ ] Find a friend. Visit their repository on github.uc.edu and file a pull request for them to merge your changes with theirs.
    * **Always commit your changes first, before you start something like this.** Your commit history doesn't have to be pretty for this project. You're still learning.
    * Take this slow and in steps. Ask one of the facilitators if you get stuck.
- [ ] Make some changes to the same file to the **same line** using the GitHub web site _and_ a text editor on your computer. Commit and push the local changes.
    * Resolve the conflicts by removing the conflict markers and committing, then pushing again.
- [ ] Process a classmate's pull request on GitHub
- [ ] I'd like for the animated GIFs to be clickable, and for a larger version of the image to load when you click on it. Create an issue for this in your forked repository.
    * I've already included Lightbox2's CSS and JavaScript, so you should be able to make this work with just a quick visit to the Lightbox documentation

### Moving right along

- [ ] Use the GitHub GUI client a feature branch for a navigation sidebar. Think of a creative way to use it to navigate between the images or sections of the page. (_Hint_: `<a name="anchorname" ...>` and `<a href="#anchorname" ...>`)
- [ ] Use the GitHub client to merge the feature branch back into `master`.
- [ ] File a pull request against this repository and ask me to incorporate your sidebar feature
- [ ] How's your site looking? Wicket. Why not publish it to the real live InterWebs using [GitHub Pages][ghpages]?


## A list of everyone's favorite dance moves

* Kevin: whatever that puppy-paws thing that Christopher Walken does in Fatboy Slim's
  _[Weapon of Choice](http://www.youtube.com/watch?v=XQ7z57qrZU8)_.

## Where to next




<!-- footnote-style hyperlinks -->
[h-collab]: https://help.github.com/articles/adding-collaborators-to-a-personal-repository/
[h-team]: https://help.github.com/articles/adding-or-inviting-members-to-a-team-in-an-organization/
[h-perms]: https://help.github.com/articles/permission-levels-for-an-organization-repository/
[g-fork]: https://guides.github.com/activities/forking/index.html
[ghpages]: https://help.github.com/articles/creating-project-pages-manually/
