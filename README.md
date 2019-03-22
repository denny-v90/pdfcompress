# pdfcompress
It allows the compression of PDF files.
This script depends on GhostScript.

## How to use

To convert all files in the current directory simply run ```pdfcompress```.
It creates a directory called **compressed**. Inside you find all compressed files.

To convert a file ```<name>.pdf```:
```
pdfcompress -f <name>.pdf
```
To change _output folder_:
```
pdfcompress -o <directory_output>
```

To choose the directory to scan pdf files:
```
pdfcompress -p <path_to_scan>
```

Parameters can be mixed...

Bye Bye
