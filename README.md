# devsecops
DevSecOps demo environment to demonstrate the use case for several security related checks.
In the past, it was quite cumbersome to perform these in CI/CD (e.g. Azure DevOps), however with all the available tools, using GitHub Actions much easier.

Uses the following:
- Perform a pen test using OWASP (Github action)
- Code testing (Security feature: CodeQL)
- DependencyScan (using Dependabot)

Wishlist:
- IaC validations
 https://github.com/Azure/arm-deploy

Migrate Azure DevOps to GitHub:
https://solidify.dev/blog/migrating-from-azure-repos-to-github
https://docs.github.com/en/actions/migrating-to-github-actions/migrating-from-azure-pipelines-to-github-actions
