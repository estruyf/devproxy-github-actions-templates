# GitHub Action templates to be used for the Microsoft's Dev Proxy

This repository contains a set of GitHub Action templates that can be used to start using the Microsoft's Dev Proxy in your CI/CD workflows.

## Usage

To use the GitHub Action templates in this repository, you need to copy the content of the template file into your workflow folder (`.github/workflows`) and update the content as needed.

## Templates

### Ubuntu

- Basic template: [devproxy.yml](./ubuntu/devproxy.yml)
- Template with caching: [devproxy-cached.yml](./ubuntu/devproxy-cached.yml)
- Template for Playwright: [devproxy-playwright.yml](./ubuntu/devproxy-playwright.yml)

### macOS

- Basic template: [devproxy.yml](./macos/devproxy.yml)
- Template with caching: [devproxy-cached.yml](./macos/devproxy-cached.yml)
- Template for Playwright: [devproxy-playwright.yml](./macos/devproxy-playwright.yml)

## Resources

More information about the Microsoft's Dev Proxy can be found in the [official documentation](https://learn.microsoft.com/en-us/microsoft-cloud/dev/dev-proxy/overview).

To know more about how these templates work, you can check the following blog posts:

- [Running a background service on GitHub Actions](https://www.eliostruyf.com/devhack-running-background-service-github-actions)
- [Using Dev Proxy in your GitHub Actions workflow on macOS](https://www.eliostruyf.com/dev-proxy-github-actions-workflow-macos)
- [Using Dev Proxy in your GitHub Actions workflow on Ubuntu](https://www.eliostruyf.com/dev-proxy-github-actions-workflow-ubuntu)
- [Caching Dev Proxy in your GitHub Actions workflows](https://www.eliostruyf.com/caching-dev-proxy-github-actions-workflows)
- [Use Playwright with Microsoft Dev Proxy on GitHub Actions](https://www.eliostruyf.com/playwright-microsoft-dev-proxy-github-actions)
