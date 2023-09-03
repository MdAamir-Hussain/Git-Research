# Windows Command Prompt (CMD) Commands

Below is a list of commonly used Windows Command Prompt (CMD) commands along with detailed explanations for each:

## cd (Change Directory)

- **Usage:** `cd [directory_path]`
- **Description:** Used to change the current working directory to the specified directory path. If no path is provided, it returns to the user's home directory.

## dir (List Directory Contents)

- **Usage:** `dir [options] [directory_path]`
- **Description:** Lists the files and directories in the specified directory. Various options can be used to customize the output, such as sorting, displaying hidden files, and more.

## mkdir (Make Directory)

- **Usage:** `mkdir [directory_name]`
- **Description:** Creates a new directory with the specified name in the current working directory.

## rmdir or rd (Remove Directory)

- **Usage:** `rmdir /s /q [directory_path]` or `rd /s /q [directory_path]`
- **Description:** Deletes the specified directory. The `/s` flag is used to remove all files and subdirectories, and the `/q` flag suppresses confirmation prompts.

## copy (Copy Files or Directories)

- **Usage:** `copy [source] [destination]`
- **Description:** Copies files or directories from the source location to the destination location.

## xcopy (Extended Copy)

- **Usage:** `xcopy [source] [destination] [/options]`
- **Description:** Similar to `copy`, but offers more advanced copying options like copying subdirectories and preserving file attributes.

## move (Move Files or Directories)

- **Usage:** `move [source] [destination]`
- **Description:** Moves files or directories from the source location to the destination location. It can also be used for renaming files and directories.

## del or erase (Delete Files)

- **Usage:** `del [file_path]` or `erase [file_path]`
- **Description:** Deletes one or more specified files.

## rename (Rename Files or Directories)

- **Usage:** `rename [old_name] [new_name]`
- **Description:** Renames a file or directory from the old name to the new name.

## type (Display File Contents)

- **Usage:** `type [file_path]`
- **Description:** Displays the content of a text file in the command prompt.

## echo (Display Messages)

- **Usage:** `echo [message]`
- **Description:** Displays a message or enables/disables the echoing of commands in the command prompt.

## cls (Clear Screen)

- **Usage:** `cls`
- **Description:** Clears the command prompt screen, providing a clean slate for new commands and output.

## ipconfig (IP Configuration)

- **Usage:** `ipconfig [/all]`
- **Description:** Displays the IP configuration for all network interfaces on the computer. The `/all` option provides detailed information.

## ping (Ping)

- **Usage:** `ping [hostname or IP address]`
- **Description:** Sends ICMP Echo Request messages to a network host to test network connectivity and measure round-trip time.

## netstat (Network Statistics)

- **Usage:** `netstat [options]`
- **Description:** Displays network statistics, including active network connections and listening ports.

## tasklist (List Running Processes)

- **Usage:** `tasklist [/options]`
- **Description:** Lists all running processes with details such as process name, PID (Process ID), and memory usage.

## taskkill (Terminate Processes)

- **Usage:** `taskkill [/options]`
- **Description:** Terminates or ends one or more running processes or applications based on their PID or image name.

## systeminfo (System Information)

- **Usage:** `systeminfo`
- **Description:** Displays detailed information about the computer's hardware, operating system, and software.

## sfc (System File Checker)

- **Usage:** `sfc [/scannow]`
- **Description:** Scans and repairs protected system files. The `/scannow` option initiates the scan and repair process.

## chkdsk (Check Disk)

- **Usage:** `chkdsk [drive_letter:] [/options]`
- **Description:** Checks and repairs disk errors on a specified drive. It can also be used to recover data from bad sectors.

## format (Format Disk Drive)

- **Usage:** `format [drive_letter:]`
- **Description:** Formats a disk drive, erasing all data and preparing it for use.

## shutdown (Shutdown or Restart)

- **Usage:** `shutdown [/options]`
- **Description:** Shuts down or restarts the computer. Various options allow you to specify a delay or reason for the shutdown.

## gpupdate (Group Policy Update)

- **Usage:** `gpupdate [/force]`
- **Description:** Forces an immediate update of Group Policy settings on the local computer.

## net (Network Commands)

- **Usage:** Various subcommands, e.g., `net user`, `net share`, `net use`. These subcommands perform various network-related tasks.

## wmic (Windows Management Instrumentation Command-line)

- **Usage:** `wmic [options] [query]`
- **Description:** Provides a command-line interface for interacting with the Windows Management Instrumentation (WMI) system for system management tasks.

## ver (Display Windows Version)

- **Usage:** `ver`
- **Description:** Displays the version of the Windows operating system currently in use.

## help (Get Help)

- **Usage:** `help [command]`
- **Description:** Displays help information for the specified command. It provides usage instructions and available options for commands.

These are some of the most commonly used CMD commands. Each command has its own set of options and capabilities, so it's important to consult the built-in help (`command /?`) or the official Microsoft documentation for more details on each command's usage.
