
## Homebrew

Homebrew is an open-source package manager for macOS and Linux that allows you to easily install software from the command line. It's often used by developers to install programming tools, libraries, and command-line utilities that aren't included with the operating system.


### 1️⃣ Basic Homebrew Setup & Info
| Command               | Explanation                                           |
| --------------------- | ----------------------------------------------------- |
| `brew -v`             | Check Homebrew version                                |
| `brew doctor`         | Diagnose potential issues (important before installs) |
| `brew update`         | Update Homebrew itself (formulae, casks info)         |
| `brew upgrade`        | Upgrade all outdated packages                         |
| `brew cleanup`        | Remove old versions and free up space                 |
| `brew help`           | Show help menu                                        |
| `brew list`           | List all installed formulae (packages)                |
| `brew list --cask`    | List all GUI apps installed via cask                  |
| `brew info <package>` | Show details of a package (version, deps, path, etc.) |


![Brew Screenshot](https://raw.githubusercontent.com/nittratan/brew/master/Screenshot%202025-10-25%20at%208.17.51%E2%80%AFAM.png)

### 2️⃣ Installing & Managing Packages    
| Command                       | Description                            |
| ----------------------------- | -------------------------------------- |
| `brew install <formula>`      | Install a package (CLI tool, library)  |
| `brew install --cask <app>`   | Install GUI app (like Chrome, VS Code) |
| `brew uninstall <formula>`    | Uninstall package                      |
| `brew uninstall --cask <app>` | Uninstall GUI app                      |
| `brew reinstall <formula>`    | Reinstall a package                    |
| `brew search <name>`          | Search packages                        |
| `brew pin <formula>`          | Prevent a package from upgrading       |
| `brew unpin <formula>`        | Allow upgrades again                   |

![Brew Services Status](https://raw.githubusercontent.com/nittratan/brew/master/Screenshot%202025-10-25%20at%208.38.51%E2%80%AFAM.png)


