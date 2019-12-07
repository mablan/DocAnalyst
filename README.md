# DocAnalyst
Given a PDF file, find and highly keywords in the text

Implements an Rmarkdown parametrized report that given a text (in pdf format)
and a list of three keywords perform the following:

* Search for keywords
* Count the their frequency
* Highlighting the paragraphs where the keyword was found

The process will be explained in detail with the first keyword. For each keyword
a table is produced with the page number (original document), line number (text 
data frame), and fragment text where it is produced. At the end a table with
all the keywords is presented. 

The ouput can be generated as an html or as pdf file

The document analyzed is stored in the data subdirectory. In this particular case, the file "Saudi_Vision2030.pdf" is analyzed
