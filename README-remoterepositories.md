# Reminders to me for setup on new machines

## Prereqs (perhaps not exhaustive - see the Octopress setup notes)
Fundamentally, generating the static HTML requires Ruby and some gems, and some gems require native compilation which means we use the dev kit, so:

- Ruby, as of 6/10/12 it's currently 1.9.2 - use <http://rubyinstaller.org> for the runtime and the dev kit.
- Dependencies - follow Octopress setup instructions at <http://octopress.org/docs/setup>.

## Local Git setup
A fully-functioning local machine needs two remotes in addition to the default origin that points to this project on Github:

- heroku - to publish; originally I'd said to use <http://octopress.org/docs/deploying/heroku> but this isn't necessary after the project's been set up w/ Heroku. Instead, just do a git remote add with the Heroku address. This address is on the Heroku site for the app in the 'Git Repo' section - for example, git@heroku.com:andrewenfield-octo.git.
- upstream - to pull changes/updates from the octopress project; for a reminder of what you need, use the subset of the instructions at <https://help.github.com/articles/fork-a-repo> - specifically, the part about configuring the upstream remote (and also about fetching/merging or pulling changes). The URL for the remote repository is git://github.com/imathis/octopress.git.