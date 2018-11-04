## iOS Project Template

A template to jumpstart your next iOS project integrating best practices and tools.

## Motivation

When working for early stage startups I frequently had to start new projects from scratch. While doing this I noticed that I am spending a lot of time doing basic project setup and integrating basic tools and best practices in all projects from scratch.

This template should save project setup time and also provide a common foundation that each team member will be accustomed to so that you don't have to think and explore the project structure and foundations. They will always be the same.

## Contains (best practices)

* [Swiftlint](https://github.com/realm/SwiftLint) integration - A tool to enforce Swift style and conventions
* [R.swift](https://github.com/mac-cain13/R.swift) integration - strong typed, autocompleted resources like images, fonts and segues
* Separate AppDelegate for app and tests
* Dev/Staging/Prod configurations
* Compiler performance profiling flags
* Cocoapods integration
* Gemfile for managing Cocoapods version
* Standard Readme
* Standard project structure
* Standard gitignore
* Base classes for handling deeplinks and notifications

## Prerequisites:
- This project needs [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html)

```
brew install cookiecutter
```

## Usage

The project uses Cookiecutter for project templating. To create a new project from this template just run:

```
cookiecutter https://github.com/pgorzelany/iOS-project-template.git
```

You will get a prompt to give a new app name. Thats it, you should have a new folder with your new app created based on this template!

## Additional configuration

You will have to manually configure the bundle id of the main target and test target.
