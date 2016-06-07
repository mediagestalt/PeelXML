# PeelXML
iPython notebook that pulls metadata from a directory of XML files.

This code uses XPath to extract specific metadata from a directory of 13,472 XML files.

I describe this code as a ‘brute force’ attack, meaning that the resulting CSV file requires a small amount of cleanup to remove brackets and quotation marks. For this reason the code continues to be _under development_ and may be subject to change in order to increase the elegance and functionality. But it works.

The XML files for the Peel’s Prairie Provinces Historical Postcards can be downloaded from the [University of Alberta Libraries Dataverse](https://dataverse.library.ualberta.ca/dvn/dv/UAL).

The postcards themselves can be viewed at the [Peel’s Prairie Provinces webpage](http://peel.library.ualberta.ca/collections.html).

### Contents of this repository

**PeelMetadata.ipynb**

- this is the master code file, in the format of an iPython notebook. If you have iPython installed on your machine, you can download this file (as well as the postcards from the above link) and run the code yourself. 
- Even if you’re a ‘non-coder’ this document describes the code and how it works, and there are embedded links for further information. Look at this file first.

**PeelOutput.csv**

- this is the raw output of the code. If you click on the link it will ask you to ‘View Raw’. Doing so will display the raw CSV in your browser. The file needs some minor cleanup, and that’s apparent when you take a look at it. 

**PeelPostcardMetadata(ver.1).xlsx**

- This is a cleaned version of the above file. Clicking on the link will prompt you to download the file.

**README.md**

- What you are reading right now is the README file.

**filecount.png**

- this is an image embedded in the PeelMetadata.ipynb file

**license**

- the terms of use for this code.

**xmlfile.png**

- this is an image embedded in the PeelMetadata.ipynb file
