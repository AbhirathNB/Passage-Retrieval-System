# Working of the assignment
## The PreProcessing
The preprocessing is done and the matrices used in the same are stored in excel sheets and added in the zip file for ease of use and assuming that no new files are added into the corpus.
In case any file is to added or if the preprocessing is required to be used, There is a function for the same and can be used.

```
def textpreProcessing():
    .
    .
    .
```

This is made to ensure that the preprocessing is not done each time the program is run, which improves the speed of it greatly.

## The Retrieval
The retrieval function uses the processed DataFrames to retrieve the top 3 results from all of the corpus.

## Points to be noted if PreProcessing
* The pdfs must be in the same directory as the python file. 
* Before running the code, do ensure that Visual Studio Code or any other Editor is opened in the directory of the corpus to ensure that the path is correctly accepted during the execution of the file
* After PreProcessing is completed, there will be 3 excels created. These will contain the tf-idf scoring and text to be retrieved.
* A functionality is also added to confirm the same and then proceed
```
df.xlsx
Text.xlsx
tf.xlsx
```
