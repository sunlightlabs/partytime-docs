For convenience, the canonical Party Time documentation is maintained in the [.dvi](http://en.wikipedia.org/wiki/Device_independent_file_format) format outputted by Donald Knuth's TeX. (Documentation is also available in [html](http://politicalpartytime.org/api/)). 

[Wikipedia](http://en.wikipedia.org/wiki/Device_independent_file_format) has this to say about the well-known DVI format:

	Unlike the TeX markup files used to generate them, DVI files are not intended to be human-readable; they consist of binary data describing the visual layout of a document in a manner not reliant on any specific image format, display hardware or printer. DVI files are typically used as input to a second program (called a DVI driver) which translates DVI files to graphical data. For example, most TeX software packages include a program for previewing DVI files on a user's computer display; this program is a driver. Drivers are also used to convert from DVI to popular page description languages (e.g. PostScript, PDF) and for printing.
	
To output markdown suitable for conversion to html, it is necessary to first recover the underlying .tex file (not included). For more, see this [stackoverflow post](http://stackoverflow.com/a/1622348) which compares the process to "trying to turn a hamburger back into a cow". 

Once the .tex file has been recovered, document conversion software like [pandoc](http://johnmacfarlane.net/pandoc/) can be used to, approximately, turn the .tex into an .md file suitable for conversion into html. 
