# Go Auto Install

This guide provides instructions for automatically installing Go on Linux systems and removing the installation file.

## Prerequisites

- Git installed on your system
- Terminal access

## Installation Steps

1.  Clone the repository:
    ```
    git clone [repository URL]
    ```

2.  Navigate to the cloned directory:
    ```
    cd [repository name]
    ```

3.  Make the installation script executable:
    ```
    chmod +x ./install.sh
    ```

4.  Execute the installation script:
    ```
    ./install.sh
    ```

5.  Update your system's PATH to include Go binaries:
    ```
    export PATH=$PATH:/usr/local/go/bin
    ```

6.  Verify the installation:
    ```
    go
    ```

7.  If Go is successfully installed, you will see the Go command usage instructions.

## Note

Ensure you have the necessary permissions to execute these commands. If you encounter any issues, please consult the official Go documentation or seek assistance from your system administrator.
