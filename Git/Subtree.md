## Git Subtree

1. **Add a subtree to a repository**

   ```bash
   git subtree add --prefix=<prefix> <repository-url> <branch> [--merge|--squash]
   ```

2. **Pull changes from a subtree**
   ```bash
    git subtree pull --prefix=<prefix> <repository-url> <branch> [--squash]
    ```
