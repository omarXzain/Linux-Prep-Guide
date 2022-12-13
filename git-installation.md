# Git

### install git:

Run the following command to install git:

```bash
brew install git || brew upgrade git
```

### git & github configuration:

- install GitHub CLI:
  - Run in terminal:
    ```bash
    brew install gh
    ```
  - run in terminal:
    ```bash
    gh auth login
    ```
  - select `GitHub.com` then `HTTPS`
  - it will ask you about GitHub credentials, Press `y` to continue.
  - select `Login with a web browser`.
  - from terminal copy your one-time code then press `Enter` to open github.com in your browser.
  - if you are not signed in, you will be asked to sign in.
  - past one-time code and click `Continue` then click `Authorize github`.

### git configuration:

**_Note_**: replace `YOUR NAME` and `YOUR EMAIL` with the name and email for your GitHub account.

```bash
git config --global user.name 'YOUR NAME'
```

```bash
git config --global user.email 'YOUR EMAIL'
```

```bash
git config --global core.editor "code --wait"
```

```bash
git config --global init.defaultbranch main
```

### [❮ Back](./README.md) | [Next ❯](./node-installation.md)
