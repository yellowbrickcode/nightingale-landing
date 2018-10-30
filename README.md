# nightingale-landing
A one page landing page for Nightingale, including about, and signup

# Commit Message Style Guide

This repo uses a semantic style for its commits. This aims to improve the quality of commits because it encourages small commits with seperation between things like bug fixes, new features. The history of the develop branch should read as a descriptive changelog. There are also tools that can be used to generate documentation from these commits for releases.

### Title

Starts with the type (in emoji), followed by a space, then a short descriptive title for the commit. Link to GH issues when appropriate. The subject should be a relatively broad area but there is currently no preset list of subjects. E.g.

- `:sparkles: Add issue template`
- `:hammer_and_wrench: Fix bug reported in #123`

### Description

A summary of the commit in the present tense. Not mandatory if the title is descriptive enough. Link to GH issues when appropriate. E.g.

- `Return x instead of y`
- `Add all required code for {feature-name}. Completes #321`

### Types

A list of pre-defined types you can choose from for your title:

- For commits that are just chores use :unamused: e.g. `:unamused: Add PR template`
- For commits related to adding new features use :sparkles: e.g. `:sparkles: Add Organisations`
- For commits related to fixing broken code us :hammer_and_wrench: e.g. `:hammer_and_wrench: Fix broken Organisation GET endpoint`
- For commits related to refactoring code and make it work better use :recycle: e.g. `:recycle: Encapsulate logic to get org list`
- For commits related to making your code or your app beautiful with style changes use :rainbow: e.g. `:rainbow: Convert tabs to spaces`
- For commits related to adding and maintaining documentation use :memo: e.g. `:memo: Add Swashbuckle to API`
- For commits related to writing or fixing tests use :mag: e.g. `:mag: Test Organisation GET endpoint`
