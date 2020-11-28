# ts-project-template

This project is a template for TypeScript projects to make the setup easier.

## Usage

1. Make sure you have the prerequisites installed. You need node.js and yarn.

2. Clone the repository:

    HTTPS:

    ```
    git clone https://github.com/TimJentzsch/ts-project-template.git
    ```

    SSH:

    ```
    git clone git@github.com:TimJentzsch/ts-project-template.git
    ```

3. Remove the `.git` folder and start a new git repository:

    ```
    git init
    ```

4. Install the dependencies:

    ```
    yarn install
    ```

5. Adjust the metadata in `package.json` and `LICENSE`.

## Tools

This project configures the following tools:

- yarn (package management)
- git (version control)
- TypeScript
- eslint (linting)
- prettier (formatting)
- jest (testing)
- husky (pre-commit/push hooks)

## Scripts

- `yarn build`: Build the TypeScript files (to `dist`)
- `yarn start`: Start the main TypeScript file
- `yarn lint`: Run eslint
- `yarn format`: Auto-format all source files
- `yarn test`: Run all tests
- `yarn coverage`: Run all tests with coverage
