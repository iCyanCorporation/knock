# Knock

**Knock** is a unified tool for managing installation statuses, virtual environments, and version control across multiple programming languages.

## Features

- Manage installations for multiple programming languages (Python, Node.js, Ruby, etc.)
- Seamlessly switch between different versions of languages
- Create, activate, and manage virtual environments (e.g., pyenv, virtualenv)
- Easy-to-use command-line interface (CLI) with GUI support
- Cross-platform support for Windows, macOS, and Linux

## Installation

To install Knock, follow these steps:

```bash
# Clone the repository
git clone https://github.com/iCyanCorporation/knock.git

# Navigate to the project directory
cd knock

# Install dependencies and setup
./install.sh
```

## Usage

Once installed, you can use Knock from the command line to manage your development environments.

```bash
# Check the installation status of all supported languages
knock status

# Create a new virtual environment for Python
knock create-env python3.10 myenv

# Switch between different versions of Node.js
knock switch nodejs 16.0.0
```

## Commands

- `knock status`: View the installation status of supported languages
- `knock create-env <language> <env-name>`: Create a virtual environment
- `knock switch <language> <version>`: Switch between installed versions
- `knock gui`: Launch the GUI version of Knock for easier management


## License
This project is licensed under the MIT License.

## Other
https://github.com/asdf-vm/asdf

