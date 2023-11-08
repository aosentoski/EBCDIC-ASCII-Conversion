# EBCDIC-ASCII-Conversion
This repo hosts the code to translate EBCDIC codes to ASCII characters and the framework to do so using a template. 

The task for this project was to convert EBCDIC files that contained both regular and packed data types in a given format into ASCII readable files. Given templates of how the files were formatted, when packed types occurred, and how long each datatype was, I was able to programmatically convert the files into ASCII. I did this by converting the entire file into binary, then iterating through the file character by character and either saving the packed number result or the corresponding EBCDIC two-digit codes. I then converted the two-digit EBCDIC codes into ASCII and recombined the data. 

If you have a similar project and have the template for how the data is formatted, please reach out. 
