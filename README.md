rexa1-metatagger
================

Mallet 0.4-based tagger for academic papers.

## advice

As a starting point for the metatagger, look at the script bin/runcrf, which starts the tagger. 

It then expects a stream of lines on stdin, each one like "path/to/input-file.pstotext.xml -> outputfile.name.xml".
