# Grep Implementation

This project is the implementation of the grep command including the support of options and multiple files.

Built with:



About

This utility is the implementation of the Unix grep command in python. It performs text pattern searches within one of more files and supports options as well.

The utility is desgined to be used through the command line, accepting input arguments and options.

The utility supports the following options for customization:

i : Case-insensitive search.
n : Display line numbers along with matching lines.
c : Display the count of matching lines.
l : Display only the names of files containing matches.
w : Search for whole words only.
H : Display file names when searching multiple files.
o : Display only the matching part of the lines.
The script efficiently reads and processes text files, providing options to display relevant information about matching lines or files.

**Prerequisites**

```python installed```
# Usage

The usage is similar to how one might use the grep command.

For example to seach for a pattern in a single file:

```
grep "pattern" filename
```

```
python grep.py "pattern" filename
```

Case-insensitive search with line numbers:

```
python grep.py -i -n "pattern" filename
```

Display only file names with matches:

```
python script.py -l "pattern" file1.txt file2.txt
```
