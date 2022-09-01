# Parsing PDFs

Extracting data from PDF is done by using [fitz](https://pypi.org/project/PyMuPDF/) package and involves the below steps:
  a)	Identify the structure of the document
  b)	Identify semantics that differentiate sections of the document
  c)	Configure rules to detect the sections
  d)	Map out different sections within the document to create an index
  e)	Extract data between sections/subsections 
  
Other Libraries/Packages:
  -	pandas: data manipulation
  -	re: text matching

# How to install dependencies
```
pip install -r src/requirements.txt
```



