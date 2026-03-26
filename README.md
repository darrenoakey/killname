# killname

![Banner Image](banner.jpg)

## Purpose

The `killname` script is a command-line utility that allows you to kill a process by specifying a substring of its name. It simplifies the process of identifying and terminating processes, especially when you don't know the exact process ID (PID).

## Usage

```bash
killname <name_substring>
```

`<name_substring>`: The substring to search for within the command line of the process you want to kill.

## Examples

1.  Kill a process containing 'firefox' in its name:

    ```bash
    killname firefox
    ```

2. Kill a process containing 'my_long_running_script.py' in its name:

    ```bash
    killname my_long_running_script.py
    ```

## Installation

1.  Save the script to a file named `killname`.
2.  Make the script executable:

    ```bash
    chmod +x killname
    ```

3.  (Optional) Move the script to a directory in your `$PATH` (e.g., `/usr/local/bin`) to make it accessible from anywhere in the terminal.

    ```bash
    sudo mv killname /usr/local/bin/
    ```

## License

This project is licensed under [CC BY-NC 4.0](https://darren-static.waft.dev) - free to use and modify, but no commercial use without permission.
