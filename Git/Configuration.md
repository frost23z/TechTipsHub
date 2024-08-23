## Git Configuration

### Using CLI

- **User Name and Email**
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "Your Email"
    ```
- **GPG Signing**
    ```bash
    git config --global user.signing key "Your Key"
    ```
- **Default Editor**
    ```bash
    git config --global core.editor "Your Editor"
    ```
- **Default Branch Name**
    ```bash
    git config --global init.defaultBranch "main"
    ```
- **Default Signed Commit**
    ```bash
    git config --global commit.gpgSign true
    ```
- **List Configuration**
    ```bash
    git config --list
    ```
- **Alias**
    ```bash
    git config --global alias.<alias-name> <command>
    ```

### Using Configuration File

Open the configuration file in your favorite editor. The configuration file is located at `~/.gitconfig` or `~/.config/git/config`.
```bash
[user]
    name = Your Name
    email = Your Email
    signingkey = Your Key
[core]
    editor = Your Editor
[init]
    defaultBranch = main
[commit]
    gpgSign = true
[alias]
    <alias-name> = <command>
```