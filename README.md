# pre-commit hook script with automatic installation of [gitleaks](https://github.com/gitleaks/gitleaks) and checks for sensitive information 🔒

✨ **Security Pre-commit Auto Script ✨

![GitHub](https://img.shields.io/github/license/matvrus/pre-commit-auto-script) ![GitHub last commit](https://img.shields.io/github/last-commit/matvrus/pre-commit-auto-script) ![GitHub issues](https://img.shields.io/github/issues/matvrus/pre-commit-auto-script)

This repository contains the `pre-commit-auto-script`, a script that helps automate the installation and configuration of `pre-commit` hooks in your Git repository. It utilizes [gitleaks](https://github.com/zricethezav/gitleaks) to enhance the security of your codebase. 😊

![Alt](data/Example0.png)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=2000&pause=1000&color=07F758&center=true&vCenter=true&multiline=true&width=700&height=100&lines=pre-commit+hook+script+with+automatic+installation;just+copy+and+run+the+following+command+%F0%9F%9A%80)](https://git.io/typing-svg)

## Requirements 📋

Before using this script, make sure you have the following dependencies installed:

- Git ✔️

- Curl ✔️

## Installation ⚙️

To install the script, simply run the following command in your terminal:

``` sh
curl -sSfL https://raw.githubusercontent.com/matvrus/pre-commit-auto-script/main/install.sh | bash
```

## Enable🔔 or Disable plugin 🔕

✅ Enable:

```sh
source on-off-gitleaks.sh; enable
```

❌ Disable:

```sh
source on-off-gitleaks.sh; disable
```

## Usage 🚀

After running the installation command, it will automatically install and configure `pre-commit` hooks for your Git repository. It also integrates `gitleaks` to scan for sensitive information in your codebase and prevent leaks. 🛡️

You can review and customize the list of available hooks in the `.pre-commit-config.yaml` file, which will be created in the root directory of your project. For example, you can add more arguments to the `.gitleaks.toml` file.

## DEMO 🎥

Wondering how the script works? Take a look at this demo:

![Alt](data/demo.gif)

![Alt](data/Example1.png)

![Alt](data/Example2.png)

🔒 Stay secure with `pre-commit-auto-script` and `gitleaks`! Happy coding! 🚀
