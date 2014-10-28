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

2. _Now_ use the GitHub GUI to "clone" this repository to your laptop. Right click on the repository name and choose "Open in Explorer" (Windows) or "Show in Finder" (OS X).
    * Press <kbd>F4</kbd> in Windows Explorer or Command+click on the icon in the Finder title bar on a Mac. **This is where the GitHub client cloned your repository.** Remember where this is, because these are the files you'll be editing with your text editor.

## References
For this exercise, you can get by with just the official GitHub.com [help site](https://help.github.com) open in a browser tab.

If you're stuck somewhere, and you'd like a visual step-by-step guide for a certain task, or if there's some overarching concept you believe you're missing and just want a show-me-everthing-GitHub-can do type reference, there's [GitHub Guides](https://guides.github.com/).

The [companion YouTube channel](http://www.youtube.com/user/GitHubGuides) has a lot of good material, too. The [GitHub and Git Foundations](www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-) play list is chock-full of bite-sized videos (~5 minutes apiece) that go over basic Git and GitHub tasks, although they're often command-line oriented.

## Activities

### Things going right
- [ ] Have a look at the revision history for the repository you just forked in the GitHub GUI.
- [ ] Make a few simple changes your own to `index.html` using a text editor. Commit them.
    * Use a good, descriptive commit message, but limit the summary line to 50 characters or less (points for style). You can use the "Description" field in the GUI if you need to provide more detail about the change.
- [ ]  Push those changes to "origin" (your github.uc.edu/github.com fork).
    * Look at the history and the "diffs" on GitHub.com and in the GUI client
- [ ] Find a friend. Visit their repository on github.uc.edu and file a pull request for them to merge your changes with theirs.
    * **Always commit your changes first, before you start something like this.** Your commit history doesn't have to be pretty for this project. You're still learning.
    * Take this slow and in steps. Ask one of the facilitators if you get stuck.
- [ ] Process a classmate's pull request on GitHub

### Things going wrong
Create a merge conflict, and then resolve it:

- [ ] Make some changes to the **same line** in the same file [using the GitHub web site](https://help.github.com/articles/editing-files-in-your-repository) _and_ a text editor on your computer. Commit and push the local changes using the GitHub GUI.
    * Usually Git is really smart about merging changes from both the remote and local ends, but this situation will create a merge conflict because Git can't figure out which file contains the changes you actually want.
    * Resolve the conflicts by removing the conflict markers (`>>>>>`, `=====`, and `<<<<<`)
    * Commit, then push again. A good commit message might be something like `Resolving merge conflict in index.html`.

### Dealing with changing requirements - tracking tasks and issues

Create an issue to track this feature request in your forked repository. Remember the issue number (probably #1) because we're going to use this later. Label it as an "enhancement."
- [ ] Let's make it so the animated GIFs are clickable, and so a larger version of the image loads when you click on it. 
    * I've already included Lightbox2's CSS and JavaScript, so you should be able to make this work with just a quick visit to the [Lightbox documentation](http://lokeshdhakar.com/projects/lightbox2/)
- [ ] Work on your local copy of the code. When you're happy with the way things look, add this somewhere in your final commit message before pushing back to GitHub: `Closes #1.` (assuming you opened issue #1 for this exercise).
- [ ] Go back to your project on GitHub and check out how issue #1 got closed automagically by your commit!

### GitHub flow - branching and pull requests
Forking, branching, merging, then creating a pull request to discuss how to incorporate changes back into a central repository is what GitHub calls [the GitHub Flow](https://guides.github.com/introduction/flow/).

- [ ] Use the GitHub GUI client a feature branch for a navigation sidebar. Think of a creative way to use it to navigate between the images or sections of the page. (_Hint_: `<a name="anchorname" ...>` and `<a href="#anchorname" ...>`)
- [ ] Use the GitHub client to merge the feature branch back into `master`.
- [ ] File a pull request against this repository and ask me to incorporate your sidebar feature.
    * We'll have a discussion about the pull request on GitHub. (You'll get email notifications when people leave comments on your pull requests.) Maybe I'll ask you to change a thing or two before I accept the pull request.
    * **This is what GitHub means by social coding**

### Onward and upward
- [ ] How's your site looking? Wicked. Why not publish it to the real live InterWebs using [GitHub Pages][ghpages]?

## A list of everyone's favorite dance moves

* Kevin: whatever that puppy-paws thing that Christopher Walken does in Fatboy Slim's
  _[Weapon of Choice](http://www.youtube.com/watch?v=XQ7z57qrZU8)_.


<!-- footnote-style hyperlinks -->
[h-collab]: https://help.github.com/articles/adding-collaborators-to-a-personal-repository/
[h-team]: https://help.github.com/articles/adding-or-inviting-members-to-a-team-in-an-organization/
[h-perms]: https://help.github.com/articles/permission-levels-for-an-organization-repository/
[g-fork]: https://guides.github.com/activities/forking/index.html
[ghpages]: https://help.github.com/articles/creating-project-pages-manually/
