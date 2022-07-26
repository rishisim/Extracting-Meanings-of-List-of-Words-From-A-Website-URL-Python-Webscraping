# Python-Multiple-Input-Dictionary
A basic Python Dictionary in JupyterLab that can take multiple words and output the definitions of those words at once.

### Overview
The dictionary was created using python pandas, the BeautifulSoup library, and the website: www.dictionary.com. The code webscrapes a modified url using the word parameter of the function `ggl_search()`. From html of the url, the function extracts the first definition typed in the website and outputs it as a string. 

The dictionary can also output multiple single-definitions of several words at once using lists. The words can come from a csv file (like in this repository) or they can come from a simple python list. 

In both cases, the dictionary outputs the word and definition in a DataFrame. Below is the DataFrame output if the code in the repository is run.

![image](https://user-images.githubusercontent.com/86998121/180902573-e2c4cd68-6668-4fc3-888a-85dd3466c6cd.png)


### Installation/Use

There are two ways to use the source code. The desktop version (full use of features) and web version (limited use of features).

1. Desktop (RECOMMENDED):
    
    a. Search up Anaconda Navigator and download the app.
    
    b. Open Jupyter Lab and upload the .ipynb file.
    
    c. Run the code.

2. Web Version: 
    
    a. Go to this link: https://jupyterlite.readthedocs.io/en/latest/_static/lab/index.html.
   
    b. Download the .ipynb file in the source code, and upload it to the workspace in the link.

**Note**: Sometimes the dictionary may not include a word or the class with which the definition is in may be different. It's also possible that the word inputted is not a word at all (for example, the number 0). Therefore, when running the code with that type of word, it may output an error called `'NoneType' object has no attribute 'text'`. If this error pops up, check the wrod you inputted into the function and change it. However, this happens rarely.
