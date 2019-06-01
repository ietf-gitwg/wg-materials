# GitHub Tooling

There are several great tools to help make better use of GitHub:

- [https://github.com/martinthomson/i-d-template](https://github.com/martinthomson/i-d-template) -- A set of Makefiles and  conventions for working on Internet-Drafts on GitHub, posting to IETF datatracker, etc.
- [https://github.com/dontcallmedom/github-notify-ml](https://github.com/dontcallmedom/github-notify-ml) -- A set of scripts and GitHub hooks that can automate weekly mails of open/closed issues, etc.
- [https://github.com/richsalz/ietf-gh-scripts](https://github.com/richsalz/ietf-gh-scripts) -- A set of scripts to automate most of the above, oriented for common workflow

A related tool is [https://github.com/draftr-js/draftr-js.github.io](https://github.com/draftr-js/draftr-js.github.io) which does real-time markdown to XML, Text, or HTML conversion.

Below is a list of possible extensions to these tools to improve the GitHub experience for WG participants:

- An app that helps users track unreviewed PRs across different GitHub draft repositories, as well as their status with respect to draft editor copies.
- A post-commit hook that will transform PR commit messages into draft change log contents.
- A tool that will ensure TODOs which require consensus reference corresponding issue numbers in the repository.
- A tool that takes issue or PR numbers and generates draft emails for the list when consensus is needed. In other words, a quick way to take discussion from GitHub to a WG list.
- Tooling to archive mailing list discussions in a repo for posterity (not sure how necessary this is given Dom's mailing list tools).
