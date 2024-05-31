# GitFlowPractise

A text-file based thing for practising Git Flow workflow. Follow the [git flow model](http://nvie.com/posts/a-successful-git-branching-model/) and take one feature per person. Don't worry about Hotfix branches for now: just concentrate on using `main`, `develop`, and `feature` branches, and use `git tag` for a release.

Read the [how to](./howto.md) section before you start.

## Work in groups

Allocate tasks below to each person in your group to do. If you are a group of 2 user 1 is doing task 1,3,5 & 7 etc. User 2 doing 2,4,6 & 8 etc. Create pull requests are merge each others changes into the develop branch & ultimately into the `main` branch. If you are a group of 5 allocate numbers 1 to 5 to each person and then again 6 to 10 to each and then 11 to 15 so each person will get three things to do. The larger the group the less there will be for each to do. Limit the group sizes to between 2 and 5.

To get your code into our text application thing:

* Push your feature branch to GitHub.
* Make a Pull Request on GitHub for merging your feature branch into develop.
* Ask someone to review your Pull Request, and give you a :+1: in a comment when they are happy.
* Merge the Pull Request on GitHub.

Get started by doing a `git clone` on this repo.


## Feature list: part 1

1. Add an answer to the question in `file1.md`.
2. Add an answer to the question in `file2.md`.
3. Add an answer to the question in `file3.md`.
4. Add an answer to the question in `file4.md`.
5. Add an answer to the question in `file5.md`.
6. Add `file6.md` with a question in it.
7. Add `file7.md` with a question in it.
8. Add `file8.md` with a question in it.
9. Add `file9.md` with a question in it.
10. Add `file10.md` with a question in it.
11. Add an answer to the question in `file6.md`.
12. Add an answer to the question in `file7.md`.
13. Add an answer to the question in `file8.md`.
14. Add an answer to the question in `file9.md`.
15. Add an answer to the question in `file10.md`.

## Release

Once all the features have been finished, one person should make a release by merging `develop` into `main`. All team members should get the latest copy of the `main` branch.

## Feature list: part 2

1. Add another question to `file1.md`
* Add another question to `file2.md`
* Add another question to `file3.md`
* Add another question to `file4.md`
* Add another question to `file5.md`
* Add an answer to the second question on `file 1.`md
* Add an answer to the second question on `file 2.`md
* Add an answer to the second question on `file 3.`md
* Add an answer to the second question on `file 4.`md
* Add an answer to the second question on `file 5.`md
* Add another question to `file6.md`
* Add another question to `file7.md`
* Add another question to `file8.md`
* Add another question to `file9.md`
* Add another question to `file10.md`
* Add an answer to the second question on `file 6.`md
* Add an answer to the second question on `file 7.`md
* Add an answer to the second question on `file 8.`md
* Add an answer to the second question on `file 9.`md
* Add an answer to the second question on `file 10.`md

## Release

Once all the features have been finished, one person should make a release by merging `develop` into `main`. All team members should get the latest copy of the `main` branch.


## Discussion topics

* Why use `develop` as the main branch instead of `main`?
* What state should `main` be in, in terms of tests?
* What happened when you pushed and pulled `develop`?
* What branches are allowed to merge into and out of `develop` and `main`?
* What does `git tag` do and why is it useful?
