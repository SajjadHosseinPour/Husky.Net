# Husky.Net

## Introduction

Husky improves your commits and more 🐶 woof!

You can use it to lint your commit messages, run tests, lint code, etc... when you commit or push. Husky supports all Git hooks.

**Features**
- Powered by modern new Git feature (core.hooksPath)
- User-friendly messages
- Supports macOS, Linux and Windows
- Git GUIs
- Custom directories
- Monorepo
- Staged-hooks! (soon)
- [dotnet-format](https://github.com/dotnet/format) Integration (soon)

If you already know what is the Husky (npm library), this is very similar but you can use Husky.Net without having node, yarn, etc.. installed with a lot of more features! 🚀🚀

## Installation

```shell
# global installation
dotnet tool install --global Husky

# local installation
cd <Your project root directory>
dotnet new tool-manifest
dotnet tool install Husky
```
*Note: With the local installation you should prefix the command with `dotnet`*
e.g. `dotnet husky`

### Setup husky for your project

```shell
cd <Your project root directory>
husky install
```

### Add your first hook

```shell
husky add .husky/pre-commit "echo 'Husky is awesome!'"
git add .husky/pre-commit
```

### Make a commit:

```shell
git commit -m "Keep calm and commit"
# `echo 'Husky is awesome!'` will run every time you commit
```

---

### Notes

Don't forget to give us a ⭐ on [GitHub](https://github.com/alirezanet/husky.net)

This library inspired and is a combination of [husky](https://github.com/typicode/husky) & [lint-staged](https://github.com/okonet/lint-staged) libraries for **DotNet**, so make sure to support them too!

### A lot of features are coming soon, so stay tuned! 👁️‍🗨️👀

