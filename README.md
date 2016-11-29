# NLP-commonsense-knowledge-extraction


Our system reads the input and output parameters from a config.properties file.
The following variables are to be set:

CORPORA_DIRECTORY: Sets the root path of the corpus. All files are recursively processed

FILE_FORMAT: Sets the type of files to be processed in the corpus. The results for our system are from txt files

OUTPUT_FILE_LOCATION: Sets the location of the results file.

OUTPUT_FILE_NAME: Sets the name of the file containing the extracted knowledge

DISCOURSE_CONNECTORS : A list of discourse connectors\footnote{goo.gl/yuXyjA} used for signifying conditional relationship.

COPULAR_VERBS : A list of copular verbs to be filtered


The code is available online on the github repository github.com/smd-faizan/NLP-commonsense-knowledge-extraction
## Steps to import and run
1. Import the code into eclipse and run the main method in HasReasoning class. 
2. You have to include three dependency jars into your classpath. They are common.io, slf4j, and kparser. 
3. The commons.io and slf4j can be downloaded from their main webpage. 
4. K-parser jar is available with the author of Sharma (2016) (https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxhcnBpdDcxMjN8Z3g6Nzc4NDg2YjkyMjliNWUxMA). 
5. The Output can be seen in the OUTPUT_FILE_NAME and is in the form of the examples given in the introduction.
