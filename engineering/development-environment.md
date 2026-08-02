# Development Environment

This document describes the standard development environment used across all Blackbone Software projects.

The goal is to provide a consistent, reproducible and productive setup for every developer.

---

## IDEs

### [Visual Studio Code](https://code.visualstudio.com/docs)

Used for:

- React
- React Native
- TypeScript
- Web development
- Documentation

### [IntelliJ IDEA](https://www.jetbrains.com/help/idea/)

Used for:

- Java
- Spring Boot
- Enterprise backend development
- Gradle
- Maven

---

## VS Code Profile

**Profile**

Blackbone Software – React Native

This profile contains the recommended extensions and settings for frontend and mobile development.

### Required Extensions

| Extension | Purpose |
|---|---|
| [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) | Consistent editor settings across development environments |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | Static code analysis |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Automatic code formatting |
| [Expo Tools](https://marketplace.visualstudio.com/items?itemName=expo.vscode-expo-tools) | Expo integration for Visual Studio Code |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | Git history, blame information and repository insights |
| [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) | Pull Request and issue integration |
| [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) | Inline diagnostics and error messages |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | File and folder icons |
| [npm IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | npm package auto-completion |
| [Path IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | File path auto-completion |

---

## Runtime

### [Node.js](https://nodejs.org/docs/latest/api/)

Node.js is the JavaScript runtime used to execute development tools and build processes.

### [npm](https://docs.npmjs.com/)

npm is used for dependency management and project scripts.

---

## Version Control

### [Git](https://git-scm.com/doc)

Git is used for distributed version control.

### [GitHub](https://docs.github.com/)

GitHub is used for source code hosting, collaboration, issues, Pull Requests, CI/CD and project planning.

Related document:

- [Branching Strategy](branching-strategy.md)

---

## Technology Stack

| Technology | Purpose |
|---|---|
| [Expo](https://docs.expo.dev/) | Cross-platform application framework and development platform |
| [React Native](https://reactnative.dev/docs/getting-started) | Framework for building native applications with React |
| [React](https://react.dev/) | User interface library |
| [TypeScript](https://www.typescriptlang.org/docs/) | Statically typed programming language based on JavaScript |
| [Expo Router](https://docs.expo.dev/router/introduction/) | File-based routing for Expo applications |
| [React Native Web](https://necolas.github.io/react-native-web/) | React Native components and APIs for the web |

---

## General Principles

- Keep the development environment simple.
- Install tools intentionally.
- Prefer official tooling over third-party alternatives.
- Keep configurations version controlled whenever possible.
- Keep dependencies up to date.
- Document important setup decisions.

---

## Further Reading

### Official Documentation

- [Visual Studio Code](https://code.visualstudio.com/docs)
- [IntelliJ IDEA](https://www.jetbrains.com/help/idea/)
- [Expo](https://docs.expo.dev/)
- [React](https://react.dev/)
- [React Native](https://reactnative.dev/docs/getting-started)
- [TypeScript](https://www.typescriptlang.org/docs/)
- [Node.js](https://nodejs.org/docs/latest/api/)
- [npm](https://docs.npmjs.com/)
- [Git](https://git-scm.com/doc)
- [GitHub](https://docs.github.com/)

### Internal Documents

- [Engineering Philosophy](philosophy.md)
- [Branching Strategy](branching-strategy.md)

---

> ## Engineering Principle
>
> **A predictable development environment is the foundation of predictable software.**
