# AdonisJS 5 Starter

AdonisJS is a backend framework for Node.js. The framework is written in TypeScript, and the application you will create using AdonisJS is also going to be in TypeScript.

This is a customized boilerplate of AdonisJS 5 API blueprint

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Running Windows/Linux/Mac OS
- You have nodejs installed on your system (>= v14)
- You have npm installed on your system (>= v6)
- You have git installed

### Installation

Clone this repo

```bash
example> git clone git@url:repository/name.git
```

- then cd into project root directory you just cloned `> cd project-directory`
- inside root project directory run `> npm install` to install project dependencies.
- create .env file by copying from prepared .env.\* file. i.e

```bash
> cp .env.example .env # create/copy .env from .env.example
```

- run `npm install` to downloads a package and it's dependencies.
- run `node ace serve --watch` to run adonis development server.
- the server accessible from a browser on `http://localhost:3333`

### Conventional Commit

1. **fix:** a commit of the type fix patches a bug in your codebase (this correlates with PATCH in semantic versioning).
2. **feat:** a commit of the type feat introduces a new feature to the codebase (this correlates with MINOR in semantic versioning).
3. **BREAKING CHANGE:** a commit that has a footer BREAKING CHANGE:, or appends a ! after the type/scope, introduces a breaking API change (correlating with MAJOR in semantic versioning). A BREAKING CHANGE can be part of commits of any type.
types other than fix: and feat: are allowed, for example @commitlint/config-conventional (based on the the Angular convention) recommends build:, chore:, ci:',docs:,style:,refactor:,perf:,test:, and others.
4. **footers other than BREAKING CHANGE:** <description> may be provided and follow a convention similar to git trailer format.

example: `git commit`

commit messages:
```bash
[type] [optional scope]: [short summary]

[body] - at least 20 characters up to 72, optional only for docs

[optional footer] - Ticket(Jira,Taiga,Superfun): X
```

for description details : https://www.conventionalcommits.org/

## Contributing

To contribute, you may follow these steps:

- Clone this repository.
- Create a branch: `git checkout -b <branch_name>`.
- Make your changes and commit them: `git commit -m '<commit_message>'`
- Push to the original branch: `git push origin <project_name>/<location>`
- Create the merge request.

## Developer(s)

- [Hadian Rahmat](hadian.rahmat@gits.id)

## Installed Add-ons/Plugin

- [Husky](https://github.com/typicode/husky)
- [commitlint](https://commitlint.js.org/)

## 3rd Party service(s)

-
