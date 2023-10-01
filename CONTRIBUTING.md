# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

## Adding Features
For every new feature, create a new branch from the develop branch with the following structure: `feature/[FEATURE_NAME]`.

## Commits
We are using the following types of change 'tags':
* `Added` for new code files and features.
* `Changed` for changes in existing functionality.
* `Deprecated` for soon-to-be removed features.
* `Fixed` for any bug fixes.
* `Security` in case of vulnerabilities.
Please use the following commit structure in every branch that you work in:
1. For the commit title use the following structure: `[TYPE_OF_CHANGE]: [SMALL_DESCRIPTION_OF_CHANGE]`. For example: `Added: Application class files`.
2. In the description you will go in more detail of what the changes are that you have made. You will denote every change that you made by making a list in markdown.
   
**Please be sure to follow these rules. It will help us by making the changelogs.**

## Pull Request Process
1. Go through your code and check if the changes added adhere to the coding standards of this project (currently still need to be added.)
2. Update the README.md with details of changes to the interface, this includes new environment
   variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in all files and the README.md to the new version that this
   Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in, once you have the sign-off of Bram (Repo owner), or if you
   do not have permission to do that, Bram will do it for you.
