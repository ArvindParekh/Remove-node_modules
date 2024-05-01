# Remove-node_modules
Bash script to recursively delete the node_modules folder from the current and sub directories to free up some space.

## How to run

- **To remove `node_modules` directories:**

  Simply run the script as described below. The script will search the current directory and all its subdirectories for directories named `node_modules` and remove them along with their contents.
  ```code
  curl -sS https://raw.githubusercontent.com/ArvindParekh/Remove-node_modules/main/remove_node_modules.sh | sh

### Important Notes

- **Be Careful**: This script will delete directories and their contents without asking for confirmation. Make sure you really want to delete these directories before running the script.
- **Dependencies**: If you're working in a project that relies on `node_modules` for dependencies, consider using a package manager like npm or yarn to manage your dependencies instead of manually deleting the `node_modules` directory.
