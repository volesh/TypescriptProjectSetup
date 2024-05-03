### Project Setup

This project is configured with the following tools and technologies:

- **TypeScript**: For writing type-safe code.
- **ESLint**: For linting TypeScript code.
- **Prettier**: For code formatting.
- **Husky**: To set up pre-commit hooks.
- **Jest**: For testing code.

### Usage

To get started, follow next steps:

 - **Clone repository**
```bash
git clone https://github.com/volesh/defaultProjectSetup.git
```
 - **Open cloned repository**
```bash
cd TypescriptProjectSetup
```
 - **Setup remote repository**
```bash
git remote set-url origin <your_repository_URL>
```
 - **Setup `package.json` file as needed**

 - **Install dependencies and push code to your repository**
```bash
npm install
git push origin <branch-name>
```

### Continuous Integration/Continuous Deployment (CI/CD)

To enable CI/CD, rename `.github/workflows-stopped/CICD.yml` to `.github/workflows/CICD.yml` and  describe the deployment steps there.


### Husky Hooks

This project uses Husky to set up pre-commit hooks. It will automatically lint your code before committing.


### Contributing

Contributions are welcome! Please feel free to open issues or pull requests for any improvements or features you'd like to see.
