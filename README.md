# e621-batch-downloader

A single, simple, out of the box python file to mass download e621 images.

The only requirement is Python 3.

To use, simply extract the files, delete downloads/deleteme.txt and edit tags.txt and blacklist.txt to your liking.  
In tags.txt, type the tags you would like to download against, with each line in the file representing a single set of tags to search against (as you would type them in e621's search).  
In blacklist.txt, type the tags that you would like to avoid when downloading, with each line in the file representing a single tag to avoid (as you would type them in e621's search). If you don't want to blacklist any tags, simply remove the placeholder text from this file.
Now run e621.py

This will create a file called files.dat.  
files.dat keeps a record of downloaded images to save time in future uses. Delete this file for a clean run.

Note that e621 throttles users that make large numbers of requests, as a result downloads will massively slow down after downloading enough files. There is nothing I can do about this.
