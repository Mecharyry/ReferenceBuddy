ReferenceBuddy
==============

ReferenceBuddy uses a bar code scanner to scan an ISBN barcode which is sent to a book repository to retrieve a Harvard reference which can be added to your project.

Code
=====
Unfortunetly the code for this project is no longer available. Stupidly the developer (me) created this code on a company laptop which was subsequently wiped after the termination of a project.......no backup?...........no backup........I can still tell you how it worked though!

Design
=======
It was made up of 4 main screens and the user would typically go through this process.

- Scanner: Scan the ISBN barcode obviously.
- Book details: All of the details available on the book scanned. This usually came from a book repository in the form of an XML file. This file was deserialised into a class which was used to display the book details to the user. This deserilisation was also used to create the Harvard reference.
- Project list: Once a book is scanned the user can add the book to a project list; if a project does not exist then one can be added.
- References list: A list of projects the user has made is shown allowing them to send a sorted bibliography to their email for inclusion in their dissertation.
- History: A recent history of books scanned is kept independent of the project list in case the user is adding the reference to more than one list.


Additional
===========
- The solution also included email support if the system crashed during use.
