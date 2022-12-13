# setup-development-environment

This guide for setting up your development environment for Linux/Ubuntu users.

## Installing and Updating the Linux App Manager

- Open terminal and run the following command:

  ```bash
  sudo apt-get update && sudo apt-get upgrade -y
  ```

  ```bash
  sudo apt autoremove -y
  ```

  ```bash
  sudo apt-get install build-essential -y
  ```

  ```bash
  sudo apt install git curl -y
  ```

## Homebrew Installation

The Missing Package Manager for macOS (or Linux)

- Run the following commands:

  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

  - After completion, follow the instructions from the resulting output or run this commands:

    ```bash
    echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/$(whoami)/.profile
    ```

    ```bash
    eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
    ```

- **_Restart your system then complete the instructions_**.
- to check brew Installation state use :

  ```bash
  brew doctor
  ```

- to install important packages

  ```bash
  brew install wget
  ```

### [Next ❯](./git-installation.md)
