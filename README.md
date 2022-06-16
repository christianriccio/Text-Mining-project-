# Text-Mining-project-


The idea of the project is to present an innovative approach to the management of pdfs and the related text extraction from them.
The process is based on the purpose of distinguishing the text belonging to the body of the pdf and that belonging to the title. Without getting lost in tedious formalisms, thanks to the pdfplumber module it is possible to obtain information for each single character of the pdf (of the type: font-size, font-type and etc.) which allows to identify clusters to which all the letters belongs of the same type and therefore formed the body (what is of interest) of the pdf. The clustering algorithm used is DBScan, well suited for the case as it is based on density and therefore proximity of points. 

## Structure of the project

3 python scripts:
-	Utils.py ---> has all the functions called inside the main
-	TextMining.py ---> is the script that allows the extraction of names from PDFs
-	NameExtraction.py ---> implements NLP routines(also POS tagging) to clean the text and extract the names 


## Example of output

The program is able to classify betwen text belonging to the body of the pdf and not belongig to it.
(See reference images)

![1](https://user-images.githubusercontent.com/56981873/174113768-6ebd7680-9e86-4369-8e2f-4db8dba6941b.png)


![2](https://user-images.githubusercontent.com/56981873/174113830-ff734166-ed39-404e-913a-42dd84af4e3c.png)



![3](https://user-images.githubusercontent.com/56981873/174113907-83316786-065a-46a5-9a2e-5f90c248125b.png)


![4](https://user-images.githubusercontent.com/56981873/174113932-fd9356ad-2f79-4da1-90e0-ffa4677b97b4.png)


![5](https://user-images.githubusercontent.com/56981873/174113964-3630a663-eb52-4bcc-a5e9-1eda30c5cd15.png)
