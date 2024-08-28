# Lab308A.4.1

due Thursday morning 

This helped me realize that append child wasn't working because the script tag is in the head and the javascript is being loaded before the HTML, so the element i'm trying to append doesn't exist yet. 

https://stackoverflow.com/questions/30014090/uncaught-typeerror-cannot-read-property-appendchild-of-null

As a result, I added defer to line 30 of the index.html
