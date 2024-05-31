# How to do this workshop

Form teams of **five**

One person in the team fork this repo into your GitHub profile: https://github.com/codex-academy/GitFlowPractise

Now add the other **4** team members as a collaborator on your fork of this repo. Do this by clicking on the Settings Tab in the forked repository. Then click **Collaborators & Teams** Add a new Collaborator at the bottom of that screen. Look up users using their GitHub usernames.

Each member should:

* Accept the invite from GitHub.
* Clone the newly forked repo onto their PC.

## Do this

### The repo owner:

Create a `develop` branch from the `main` and push it remotely.

```sh
git branch develop
git push origin develop
```

### Other collaborators

After the develop branch was created by the repo owner - fetch the remote `develop` branch by doing a `git fetch`.

Be sure you can check out the `develop` branch locally using `git checkout develop` - you will create all your feature branches from the `develop` branch.

To create a feature branch do this:

```sh
git branch the_feature
git checkout the_feature
```

Do your work on the feature branch.

Once done add & commit your changes onto the feature branch and then push it to the central repo.

```sh
git push origin the_feature
```

Now issue a pull request to your team members using @their usernames to merge into `develop`. Delete the branch as part of doing the pull request GitHub will give you the option to delete the branch.

Once done delete the feature branch locally:

```sh
git branch -d the_feature
```

Once the merge is done using the pull request - update your local `develop` branch using a `pull`.

```sh
git pull origin develop
```





