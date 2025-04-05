# File Handling and Exception Handling in Python
This is a Python program that reads a file, modifies its content, and writes to a new file with comprehensive error handling.

## How It Works:
1. User Input: Asks for input and output filenames

2. Error Handling:
   - FileNotFoundError: Handles case when input file doesn't exist
   - PermissionError: Handles read/write permission issues
   - UnicodeDecodeError: Handles non-text files
   - General IOError: Catches other file-related errors
   - Catch-all Exception: For unexpected errors

3. File Operations:
   - Reads the input file in a try block
   - Modifies the content (in this case converts to uppercase)
   - Writes to the output file in a nested try block

4. Modification: The example converts text to uppercase, but you can replace this with any modification logic you need.

## Example Usage:
 ```
    Enter the name of the file to read: input.txt
    Enter the name of the output file: output.txt
    Successfully processed file. Output written to output.txt
 ```
## Or if there's an error:
 ```
Enter the name of the file to read: nonexistent.txt
Error: The file 'nonexistent.txt' does not exist.t
 ```
