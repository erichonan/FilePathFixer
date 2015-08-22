A simple script to easily convert ugly file paths into clickable file paths.

Background:
I receive a lot of file paths from project managers who are working on PCs. These paths are often 10+ directories deep and the directory names often include spaces. Rather than taking the extra minute to manually select the server and navigate through all of the folders I would like this script to do the dirty work for me. A simple solution for a simple problem.

This script currently
	- accepts a string via input field and escapes all spaces

And this script should eventually
	- be executable after selecting in any document
	- correct server prefix for mac
	- ideally, auto check available servers and alert user if server is unavailable