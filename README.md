# ImageToPDF

ImagetoPDF is a command-line tool for generating a PDF.
You simple call the exe in a folder full of content (usually images) that you want to compile into a single PDF.

Sometimes, I get art books from....places that start with e-\*.org and ex*.org and the books come in as a dump of about 200 scanned images.
I like to view these books in the form of a PDF.

## Installation

Download the exe and run it in a folder full of images (via command-line).

Better yet, put the exe in path somewhere and add said path into your Environment Variables.
I do this because I use this tool fairly frequently.

## Usage

Call ImagesToPDF in command-line in a folder full of images.
You will get a list of files, sorted by name. Ideally, the image files are numbered, so they are sorted appropriately. If not, you will have to figure that out.

Under the list, you will be prompted to confirm the conversion. The PDF will automatically use the name of the directory as the PDF file name, which you can see and review before confirming.

Enter Y/y to start the conversion. Any other input will cancel the operation.

Lastly, as long as the command-line window it opened, the image files will be "locked". So close the command-line window and then you may delete the image files, if desired.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
