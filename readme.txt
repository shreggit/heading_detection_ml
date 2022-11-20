This is an NLP approach to building a Heading Detection Model. 
The objective of this project is to classify a given field of a contract as either a clause heading or not. 
The dataset was created by taking 100's of contracts and extracting features from the text. 
I initially used a PDF to HTML converted, but later changed to the Adobe Extract SDK which converts a pdf to a json file. 
Using font information such as font size, bold/not, POS tags such as number of nouns, verbs, cardinal digits and so on, as well as enumeration tag and text case, I built various feature vectors that enabled to build an accurate ML classifier.
I used a Gradient Boost ML classifier to train the data using the sklearn library. 
Please use a JSON file which you can get converted using the ADOBE API, to test your document for headings. 
