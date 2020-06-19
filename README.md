# Boiler template for NodeJS project with TypeScript🎉

created: 2020-06-19T13:48:17.539Z
updated: 2020-06-19T14:20:46.152Z

## Purpose

_Boiler Template for NodeJS project with TypeScript_.

We can start a new project with this clean template with TypeScript that keep the code better.

## Install

1. Clone this repository. Please replace `YOUR_PROJECT_NAME` to the real name.

   ```bash
   git clone https://github.com/koheitakumi/node-template-with-typescript.git YOUR_PROJECT_NAME
   ```

1. Rename the project name

   - package.json
     - name
     - version
     - repository
     - author
     - license
   - remove src/index.ts
   - change contents as you like
     - .vscode/settings.json
     - .editorconfig
     - .gitignore
     - .prettierrc.js
     - tsconfig.json

1. Make your new repository on your Git service like GitHub.

1. Commit these changes and push it into your Git repository. Please replace `YOUR_GIT_REPOSITORY_URL` to your repository URL.

   ```bash
   git commit -m "first commit"
   git remote add origin YOUR_GIT_REPOSITORY_URL
   git push -u origin master
   ```

- Great! You can start your new Project now!🙌

## Usage

Please check the package.json.

### Run TypeScript code each time.

```bash
npm run dev
# or
yarn dev
```

### Watch code changes.

It's useful when you develop server side application

```bash
npm run dev:watch
# or
yarn dev:watch
```

### Clean compiled code in dist.

```bash
npm run clean
# or
yarn clean
```

### Run tsc command

```bash
npm run tsc
# or
yarn tsc
```

### Build this project into dist for publish.

```bash
npm run build
# or
yarn build
```

### Run the built project.

```bash
npm run start
# or
yarn start
```

### Execute lint to check your code.

```bash
npm run lint
# or
yarn lint
```

### Format your code.

```bash
npm run format
# or
yarn format
```

### Stage code on your repository.

```bash
npm run precommit
# or
yarn precommit
```

## Preference

- [VSCode: User and Workspace Settings](https://vscode.readthedocs.io/en/latest/getstarted/settings/)
- [tsconfig.json document](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
- [Configuring ESLint](https://eslint.org/docs/user-guide/configuring)
- [Prettier vs. Linters](https://prettier.io/docs/en/comparison.html)
