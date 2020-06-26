# Review

In this workshop, we've

- Forked a repository
- Created a new branch on the fork
- Created a new file in the new branch 
- Committed our edits
- Opened a pull request to merge our commit into the master branch of the source repository
- Looked at the owner's review options

What should you now do with the branch you created in your fork? You have some options.

- You could just leave it alone, though over time, if you create a lot of branches, you might find the clutter confusing.
- You could delete it and create another new branch the next time you want to contribute new content in the source or suggest edits to existing content there.

What about your master? It's now out of sync with the source. What to do about that?

- You could merge your new branch into your own master, though that's not the ideal way to keep your master in sync with the source repository.
- You could follow [these instructions for syncing your master with the source's master](https://www.sitepoint.com/quick-tip-sync-your-fork-with-the-original-without-the-cli/) using the GitHub web interface. The process described in these instructions is the reverse of the one you just carried out. Instead of opening a pull request to merge *your* changes into the *upstream* repository (i.e., the one you forked), you open a pull request to merge the latest *upstream changes* into *your fork*. Since you're the owner of your fork, you'll be asked to approve the merge. Once you do that, your fork will be up to date with upstream.
- *You could take the plunge and learn to use Git from the command line*, which would make synchronizing repositories and all your other tasks much easier. Yes, there's a learning curve involved, but it's worth it.

You'll find instructions on getting started with command-line Git in the [DHRI workshop from which we've forked this one](https://github.com/DHRI-Curriculum/git).

Let's wrap up by looking at some examples of how people are using Git and GitHub for DH projects.

[<< Previous](reviewpull.md) | [Next >>](dhexamples.md)
