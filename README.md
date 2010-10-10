pymime - A MIME formatter in python
===================================

This program is designed to take a MIME-formatted email and to do various transformations with it, e.g.
converting HTML-mail to plain text mail and stripping attachments.

Usage
-----

	Usage: pymime.py [options]
	Options:
	  -h, --help
	            show this help message and exit
	  -i INPUT, --input=INPUT
	            Where to read the mail from. Defaults to STDIN
	  -o OUTPUT, --output=OUTPUT
	            Where to write the transformed mail. Defaults to STDOUT
