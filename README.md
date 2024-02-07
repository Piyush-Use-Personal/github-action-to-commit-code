```
# Github action to make code commits

## Description

This project implements a GitHub Action workflow that automatically runs ESLint to fix linting issues in a Node.js project, commits the changes, and pushes them back to the same branch with a designated user account.

## Usage

1. **Configuration**:
   - Ensure you have ESLint configured in your project, including the `npm run lint:fix` script to fix linting issues.
   - Set up a designated user account on GitHub that will be used for committing changes made by the GitHub Action.

2. **GitHub Action Workflow**:
   - Create a GitHub Action workflow file (e.g., `.github/workflows/lint.yml`) in your project repository.
   - Copy and paste the provided workflow content into the workflow file.
   - Adjust the workflow triggers, Node.js version, and branch name according to your project requirements.
   - Commit and push the workflow file to your repository.

3. **Execution**:
   - Upon every push to the specified branch, the GitHub Action will automatically:
     - Check out the code.
     - Set up Node.js and install dependencies.
     - Run ESLint to fix linting issues.
     - Commit the changes with the designated user account.
     - Push the changes back to the same branch.

## Dependencies

- ESLint: An open source JavaScript linting utility.
- GitHub Actions: A continuous integration/continuous deployment (CI/CD) service provided by GitHub.

## License

This project is licensed under the [MIT License](LICENSE).
```
