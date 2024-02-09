# 🚀 Multi-User Creation Script

This script allows you to create multiple users on a Unix-based system using a simple text file. It's perfect for system administrators who need to set up multiple user accounts quickly and efficiently.

## 🌟 Features

- **👥 Batch User Creation**: Create multiple users in one go.
- **🔑 SSH Key Setup**: Automatically sets up SSH keys for each user.
- **⚠️ Error Handling**: Gracefully handles errors such as duplicate users or missing SSH key files.

## 📖 Usage

1. Prepare a `user.txt` file with each line containing a username, password, and the path to the SSH public key file, separated by spaces. For example:

    ```
    user1 password1 /path/to/ssh/key1
    user2 password2 /path/to/ssh/key2
    user3 password3 /path/to/ssh/key3
    ```

2. Run the script with root privileges and `chmod +x multiusercreate`:

    ```bash
    sudo bash multiusercreate
    ```

3. The script will create the users and set up their SSH keys. If a user already exists or the SSH key file is missing, the script will skip to the next line.

## ❗ Note

Please ensure that the `user.txt` file is accurate and the SSH key files exist at the specified paths. The script needs to be run with root privileges to create users and set up SSH keys.

Enjoy your new user accounts! 🎉

