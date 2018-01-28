This directory contains R Markdown files that I need to convert to Markdown before adding to the _posts directory. So far, I have not created any good automation for this process, but I hope to in the future. Right now, I do the following.

1. knit R Markdown to HTML with the option of a stand-alone Markdown file. 
2. remove HTML files. 
3. Copy over markdown file to _posts directory as well as any necessary assets like data files or images to the assets file.
4. Manually correct paths in the markdown file to point correctly at assets. 
