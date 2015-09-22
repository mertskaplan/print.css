# Printable pages with 'print.css'
##### It's simple!
Just add this line between **<head>** and **</head>** tags in your pages.
> &lt;link rel=&quot;stylesheet&quot; href=&quot;print.css&quot; media=&quot;print&quot;&gt;

And use
> .non-printable

class for things that you do not want to print.

Or use 
> .printable

class for invisible things that you want to print.


### A simple example:
> &lt;div class=&quot;non-printable alert&quot;&gt;Status was changed successfuly.&lt;/div&gt;