

Customize Virtual File System (CVFS) in C

This project is an implementation of a Customize Virtual File System (CVFS) in C. The CVFS provides a set of file operations similar to those found in a real file system, allowing users to work with files and directories.

### Features

1. **File Creation**: Users can create new files with specified permissions.

2. **Opening Files**: Existing files can be opened in various modes, such as read-only or read-write.

3. **Reading and Writing**: Users can read data from files and write data to files. These operations respect file permissions.

4. **Listing Files**: The CVFS can list all available files, providing information about each file, such as its name, size, and inode number.

5. **File Information**: Users can retrieve detailed information about a specific file, including its inode number, size, link count, and permissions.

6. **File Truncation**: Files can be truncated, effectively removing all data from the file.

7. **File Deletion**: Users can delete files from the CVFS.

8. **File Seeking**: The CVFS supports file seeking, allowing users to change the file offset for reading or writing.

### Usage

To use this Customize Virtual File System (CVFS), you need to compile the provided code (`CVFS.c`). Follow these steps:

1. Clone this GitHub repository to your local machine.

2. Open a terminal and navigate to the project directory.

3. Compile the code using a C compiler. For example:

   ```shell
   gcc CVFS.c -o cvfs
   ```

4. Run the compiled program:

   ```shell
   ./cvfs
   ```

5. You'll be presented with a command-line interface (CLI) to interact with the CVFS. Use commands like `ls`, `create`, `read`, `write`, `stat`, and others to perform file operations.

### Commands

The CVFS supports several commands:

- `ls`: List all available files.
- `create`: Create a new file with specified permissions.
- `open`: Open an existing file in a specific mode (read, write, read-write).
- `read`: Read data from a file.
- `write`: Write data to a file.
- `exit`: Terminate the CVFS.

For more detailed information on supported commands and their usage, run the `help` command within the CVFS CLI.



### Contribution

Contributions to this project are welcome! If you have any suggestions, bug fixes, or improvements, please feel free to create a pull request or open an issue.

### Acknowledgments

This CVFS project is based on a simple file system implementation and is meant for educational purposes. It demonstrates basic file operations and can serve as a starting point for more complex file systems.

