# GitHub Actions CI Templates

A repository of templates for JavaScript and Node.js GitHub Actions CI configurations using the latest version of every available OS, plus all versions of Node.js officially supported by the Node.js project.

## How to use the Templates

Add the appropriate YAML to your repository under the `.github/workflows/` path, naming the YAML whatever you'd like to name it. I generally like to follow the `language-platform(s)-ci.yaml` pattern, but your mileage may vary.

For example, if you wanted to use the `nodejs-cross-platform-ci.yaml` template, you'd add it in:

```bash
- .github/
  - workflows/
    - nodejs-cross-platform-ci.yaml # you can rename this whatever you'd like
```

## How to improve the Templates

If you'd like to improve the templates provided, you're more than welcome to submit a PR! If you notice a template that's entirely missing but you'd like to see, feel free to send a Pull Request to add it yourself _or_ create an issue requesting it to be added.