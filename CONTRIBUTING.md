To read more about contributing to open source see https://opensource.guide/

# Submitting a PR

**All Pull Requests should be made against dev (even bug fixes).**

Before submitting a large PR for a new feature or improvement, please create an issue first. This will allow us to discuss the feature before much development effort is put into it. After we've agreed that the feature would fit in the scope of the project, or if the change is small enough to not require an issue, follow these steps to create a PR:

- Make a new branch

git checkout -b my-fix dev

- Make your changes, including test cases if applicable. Make sure to follow the coding guidelines described below.
- Commit your errors with a descriptive message

git add my-new-file.xyz modified-file.xyz

git commit

- Push your changes to Github

git push origin my-fix

- Create a new Pull Request
- We will review your PR and request changes if necessary.
- When you make a new commit fixing a requested change, please squash your changes using git rebase.
- Once all requested changes have been made, we will merge your pull request.


# Coding Guidelines

- Wrap lines at 100 characters
- Use spaces not tabs
- New lines should be indented by two spaces
- Never add a trailing comma to multiline lists in JS
- Don't add extra spaces between parenthesis, i.e. do foo(1, 2), not foo( 1, 2 )
- Always use spaces around binary operators, i.e. $i = 0, not $i=0
- Use camelCase for variables and PascalCase for class constructors.
