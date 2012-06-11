# Reminders to me for setup on new machines

## Prereqs (perhaps not exhaustive - see the Octopress setup notes)
Fundamentally, generating the static HTML requires Ruby and some gems, and some gems require native compilation which means we use the dev kit, so:

- Ruby, as of 6/10/12 it's currently 1.9.2 - use <http://rubyinstaller.org> for the runtime and the dev kit.
- Dependencies - follow Octopress setup instructions at <http://octopress.org/docs/setup>.

## Local Git setup
A fully-functioning local machine needs two remotes in addition to the default origin that points to this project on Github:

- heroku - to publish; use <http://octopress.org/docs/deploying/heroku> - I think only the setting up the remote is necessary if the rest of the content is one-time setup w/ Heroku for the project itself.
- upstream - to pull changes/updates from the octopress project; use <https://help.github.com/articles/fork-a-repo> as a reminder.