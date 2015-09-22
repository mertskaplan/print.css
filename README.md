# Printable pages with 'print.css'
##### It's simple!
Just add this line between **<head>** and **</head>** tags in your pages.
> <link rel="stylesheet" href="print.css" media="print">

And use
> .non-printable

class for things you do not want to print.

Or use 
> .printable

class for invisible things that you want to print.


### A simple example:
> <div class="non-printable alert">Status was changed successfuly.</div>