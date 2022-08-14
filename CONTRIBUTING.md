# Contributing to oas-tools

We would like to thank you for your interest in contributing to this project. We are open to issues and pull requests, and we really appreciate any help from the community. However, for better management of your contributions, we encourage you to follow some guidelines. We will not ignore nor delete a contribution which does not follow these guidelines, but we could take longer to review and accept it.

## Issues

We will consider two diferent types of issues: **bugs** and **suggestions** (including enhancements, questions, optimizations...). Nevertheless, there are some common considerations to take into account:
* Please do not create an issue referencing multiple problems. Instead, **create as many issues as bugs you have found or suggestions you want to send**.
* **Check other open and closed issues** to see if your problem has been reported before.
* You may **close an issue if you think that it is no longer relevant**. We appreciate any comment explaining why it was closed so that we know what happened.
* After submitting an issue, **we will review it and add a label** with its corresponding type.
* Note that due to several factors, **an issue may be delayed for a future version**. In the same way, **an issue could be solved and released faster**.
* Use our **Issue template** when creating an issue.
* If you are not sure about something, feel free to start a discussion in our [GitHub discussions board](https://github.com/orgs/oas-tools/discussions?collapsed=1).

### Bugs

These issues refer to something that is not working properly. We recommend following these steps:
* **Write a descriptive title**, explaining what feature is not working.
* In the description, **explain the steps required to reproduce the bug**.
* **Include the expected and the actual result** to better understand the problem.
* It may be useful to **include log fragments**. Remember that you can change the log level to retrieve more information.
* It may be useful to **include the OpenAPI Specification file** that you are using or a fragment of it, so that we can use it to reproduce the bug.
* You can **add the affected code fragment** if you think that you have found the cause of the bug.

### Suggestions
These issues refer to enhancements and new features, questions about oas-tools or even performance optimizations. These are the recommended steps for this kind of issue:
* **Write a descriptive title**, explaining what your suggestion is.
* In the description, **include a detailed explanation of the suggestion**.
* You can **add fragments of code or pseudocode** to better describe what you are suggesting.

## Pull requests

If you fix a bug or implement a suggestion, we greatly appreciate any pull request. These are the considerations to take into account when creating a pull request:
* We like to work in the `develop` branch and make a pull request to `main` when a new version is going to be released. Therefore, we recommend **creating the pull request to the `develop` branch**.
* If there is no related issue, please **create a new issue and add a reference to it** in the pull request.
* Do not create a single pull request for multiple issues. Instead, **create as many pull requests as issues you have solved**.
* It may be useful to **include a brief description of the issue**. The detailed explanation should be in the issue itself.
* **It is not necessary to add any reviewer**. We will make sure to check for new pull requests periodically.
* If all checks are passing, **we will merge the pull request and its content will be available in the next version**.
* We greatly encourage to use **CONVENTIONAL COMMITS** format for your commits, since the version is automatically set by the CI based on the commits. You can check the commits format [here](https://www.conventionalcommits.org/en/v1.0.0/)