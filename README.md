# devsecops
DevSecOps demo environment to demonstrate the use case for several security related checks.
In the past, it was quite cumbersome to perform these in CI/CD (e.g. Azure DevOps). Using GitHub (actions) and all the available security tools, secure development is a lot easier than it used to be.

Uses the following:
- Perform a pen test using OWASP (Github action)
- Code testing (Security feature: CodeQL)
- DependencyScan (using Dependabot)

Wishlist:
- IaC validations
 https://github.com/Azure/arm-deploy

Github security:
https://github.com/security

CodeQL (define queries against your code)
https://codeql.github.com/


Migrate Azure DevOps to GitHub:
https://solidify.dev/blog/migrating-from-azure-repos-to-github
https://docs.github.com/en/actions/migrating-to-github-actions/migrating-from-azure-pipelines-to-github-actions
