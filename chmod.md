- Permissions
  - Permissions can be set to 644 for files and 755 for folders. To do so, you can run two quick find commands.
  - To make all folders in your website path with 755 permissions run the following command
  ```bash
  find /path/to/website -type d -exec chmod 755 {} \;
  ```
  - To make all files in your website root directory with 644 permissions, you can run
  ```bash
  find /path/to/website -type f -exec chmod 644 {} \;
  ```


- Ownership
  - Ownership means which user and group are controlling the files. Usually, that’s www-data. So what you’ll need to do si
  ```bash
  sudo chown -R www-data:www-data /path/to/website
  ```
