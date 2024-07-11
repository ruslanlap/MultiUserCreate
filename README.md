# 🚀 Multi-User Creation Script

This script allows you to create multiple users on a Unix-based system using a simple text file. It's perfect for system administrators who need to set up multiple user accounts quickly and efficiently.

## 🚀OMGFeatures

- **👥 Batch User Creation**: Say goodbye to repetitive user creation tasks. UserGenius allows you to create multiple users in one go, saving you time and effort.
- **🔑 SSH Key Magic**: UserGenius automagically handles SSH key setup for each user. No more manual configuration needed.
- **⚠️ Error Handling Wizardry**: UserGenius performs error handling with finesse, gracefully handling duplicate users or missing SSH key files like a true genius.

## 📖 Usage

1. Prepare your supercharged `user.txt` file. Each line should contain a username, password, and the path to the SSH public key file, separated by spaces. Unleash your creativity! Here's a sample to get you started:

    ```plaintext
    user1 password1 /path/to/ssh/key1
    user2 password2 /path/to/ssh/key2
    user3 password3 /path/to/ssh/key3
    ```

2. Embrace your admin powers and run the script with root privileges. Make it executable using the command:

    ```bash
    sudo chmod +x multiusercreate
    ```

    Then, initiate the superuser creation process:

    ```bash
    sudo ./multiusercreate
    ```

3. Witness the magic unfold! UserGenius will create the users and perform the SSH key setup. If a user already exists or the SSH key file is missing, UserGenius will gracefully skip to the next line, ensuring a seamless user creation experience.

## ❗ Note

To fully unleash the power of UserGenius, ensure the accuracy of your `user.txt` file and verify the existence of the specified SSH key files. Remember, UserGenius needs to be invoked with root privileges to manifest its genius abilities.

Get ready to embrace your inner genius and enjoy the wonders of UserGenius! 🎩✨
