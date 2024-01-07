# ImageToPDF

ImagetoPDF is a command-line tool for generating a PDF.
You simple call the exe in a folder full of content (usually images) that you want to compile into a single PDF.

Sometimes, I get art books from....places that start with e-\*.org and ex*.org and the books come in as a dump of about 200 scanned images.
I like to view these books in the form of a PDF.

This was inspired by [minisoftwarelab's solution](https://github.com/minisoftwarelab/imap-Image-to-PDF-Converter-Application-For-Windows), but I wanted something faster and less cumbersome to use.

## Installation

Simply run the installer.
Unfortunately, it has only been tested on Windows 10 and needs .NET 7.0

The installer does four things:
- Copies the main ImageToPDF.exe to the installation directory
- Creates an uninstaller
- Creates a Start Menu link to the uninstaller
- Adds the installation directory to the system's PATH Environment Variables

It only adds to the PATH variable if you answer yes to the related prompt, but I would recommend that you do this.

## Usage

Call ImageToPDF.exe in command-line in a folder full of images.
You will get a list of files, sorted by name. Ideally, the image files are numbered, so they are sorted appropriately. If not, you will have to figure that out.

Under the list, you will be prompted to confirm the conversion. The PDF will automatically use the name of the directory as the PDF file name, which you can see and review before confirming.

Enter Y/y to start the conversion. Any other input will cancel the operation.

Lastly, as long as the command-line window it opened, the image files will be "locked". So close the command-line window and then you may delete the image files, if desired.

https://github.com/HueVirtualCreature/ImageToPDF/assets/108766452/0cbcbb97-1f28-4600-8483-7ab0b6d4c8b9

## Contributing
No
