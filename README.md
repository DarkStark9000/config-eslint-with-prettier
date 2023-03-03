# Config files for future reuse and avoiding conflict

This repository contains ESLint and Prettier JSON config files to be used in projects made with Create-React-App. The ESLint config uses the base Airbnb style and has some custom rules modifications.

## What does this repo contain?

This repo has:

- `.eslintrc` file
- `.prettierrc` file
- `.gitignore` file

## How to use these files?

1. Create a React project folder using `npx create-react-app` or building it from scratch.
2. Copy the files `.eslintrc`, `.prettierrc`, and `.gitignore` to your project root.
3. Run the following commands one after the other:

```md
npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node
npx install-peerdeps --dev eslint-config-airbnb
```


## Are there any conflicts?

The `.eslintrc` and `.prettierrc` files have been configured and tested to write React code using JSX syntax. There have been no reported conflicts.

## Are there any dependencies that need to be satisfied?

The `.eslintrc` has been configured so that it can be used with any version of React. 
