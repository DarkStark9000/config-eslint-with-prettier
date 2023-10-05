# React Config Starter Pack

This repository serves as a starter pack to configure ESLint, Prettier, and other dev tools in a Create-React-App project. By following the provided ESLint and Prettier rules, you can enforce a consistent code style and avoid common errors. These configurations are based on the Airbnb style guide and include custom rule modifications for your ease.

## Table of Contents

- [React Config Starter Pack](#react-config-starter-pack)
  - [Table of Contents](#table-of-contents)
  - [What Does This Repo Contain?](#what-does-this-repo-contain)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Conflict Resolution](#conflict-resolution)
  - [Dependencies](#dependencies)
  - [Contribution](#contribution)

## What Does This Repo Contain?

- `.eslintrc.json`: Contains the ESLint configuration
- `.prettierrc.json`: Contains the Prettier configuration
- `.gitignore`: Standard git ignore rules

## Prerequisites

- Node.js installed on your system
- Create-React-App (CRA) or a React project setup

## Installation

1. Clone this repository or copy the `.eslintrc.json`, `.prettierrc.json`, and `.gitignore` files into your React project root directory.
2. Open your terminal and run the following commands:

```bash
npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node
npx install-peerdeps --dev eslint-config-airbnb
```

## Conflict Resolution

The .eslintrc.json and .prettierrc.json files have been tested for compatibility with React and JSX syntax. In case of any issues, please refer to the Contribution section.

## Dependencies

These configurations are designed to be compatible with any version of React.

## Contribution

Feel free to contribute to this repository by creating a pull request or raising an issue for any conflicts or improvements.
