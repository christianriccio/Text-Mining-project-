# Text-Mining-project-


The idea of the project is to present an innovative approach to the management of pdfs and the related text extraction from them.
The process is based on the purpose of distinguishing the text belonging to the body of the pdf and that belonging to the title. Without getting lost in tedious formalisms, thanks to the pdfplumber module it is possible to obtain information for each single character of the pdf (of the type: font-size, font-type and etc.) which allows to identify clusters to which all the letters belongs of the same type and therefore formed the body (what is of interest) of the pdf. The clustering algorithm used is DBScan, well suited for the case as it is based on density and therefore proximity of points. 

## Structure of the project

3 python scripts:
-	Utils.py ---> has all the functions called inside the main
-	TextMining.py ---> is the script that allows the extraction of names from PDFs
-	NameExtraction.py ---> implements NLP routines(also POS tagging) to clean the text and extract the names 


## Example of output
