# Book Structure
In the root folder of each book, you'll usually find the following files:

* README.md - this is a brief synopsis of the book.

You'll also find a **manuscript** folder, which is where the rest of the book lives.

* book.txt is the Table of Contents for LeanPub. It reads the chapter filenames from this, and then uses the heading from the top of each chapter file to build the ToC.
* Chapter files must have the .md filename extension - please don't use .txt.
* About.md is always our standard boilerplate.

The **images** folder must contain any and all images for the book, including the title_page.jpg (or .png) file that LeanPub uses for the cover image.

Any attachments (code samples, ZIP files etc) should go into an **attachments** folder under the root (at the same level as **manuscript**, not under it). Neither GitHub nor LeanPub will do anything with these; you should provide links to these files in the main GitHub repository.

