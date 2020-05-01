# Contributing to React Easy Tabs

Thank you for taking an interest in this project 🙏

Here are a few guidelines to keep in mind if you'd like to contriibute to React Easy Tabs.

Message from Alex: _"My apologies! This guide is still being developed"_

## Code of Conduct

The Code of Conduct can be found _[here](./CODE_OF_CONDUCT.md)_.

## Style Guide

### Git Commit Messages

We're following Angular's [commit message guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#commits).

#### Format

A commit message contains a:

- Header: This has a type, a scope, and a subject
- Body
- Footer

```git
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The header is mandatory.

Example with just the header:

```git
    docs(contributing): update style guide
```

A line in the commit message should **_not_** exceed 100 characters. Additionally, and we should follow these rules:

- Use the imperative, present tense: use "change", not "changed" nor "changes"
- The first letter should **_not_** be capitalized
- No dot/period (.) at the end
- If this commit reverts a previous commit: Begin with `revert:`, followed by the header of the reverted commit
- If this commit reverts a previous commit: Begin with `BREAKING CHANGES:`, followed by a space or two new lines

#### A breakdown of the sections of a commit message

##### Type

These are the different types of commits:

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding missing or correcting existing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

##### Scope

This is _optional_.
It specifies the place of the commit change.

##### Subject

A concise description of the change.

##### Body

Tells us the reason for the change, and contrast this with previous behavior.

##### Footer

Holds the information about any breaking changes.
