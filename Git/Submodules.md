## Git Submodules

1. **Add a submodule**

   ```bash
   git submodule add <repository-url> [<path>]
   ```

2. **Update a submodule**

   ```bash
    git submodule update --remote
    ```

3. **Remove a submodule**

   ```bash
   git submodule deinit <path>
   git rm <path>
   rm -rf .git/modules/<path>
   ```

4. **Clone a repository with submodules**
   ```bash
    git clone --recurse-submodules <repository-url>
    ```