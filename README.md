# nlp_pdf
Use of python libraries (pdfminer, NLTK, spaCy) to parse scientific journal PDF files and extract specific keywords such as: taxonomy, nsc (unique identifier), authors, compound name. Used to aid extraction of pertinent information from journal articles and enter into spreadsheets. An ensemble class vote was used to classify keywords based on training set (`taxon_names.csv`)

#### Info
There are three serparate `.ipynb` files. The file with `_ML` extension was written by colleague using TFID method (not implemented but kept for reference). The file with `_short_version` extension was used for presentation. The file with no extension is the original version. Models must be compiled in the jupyter notebook since file size was too big to include in repo. There is a function to save the picklise the model and save to local machine in order to speed up subsequent runs. 
