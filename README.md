Semantic analysis project using NLP methods to determine latent semantic shifts in certain politically charged words over time.
Initially created as a google colab notebook. 

To run as-is, without any modification:
1. Download the notebook and the .zip file to a project folder OR git clone the repository.
2. Unzip the .zip file inside of the project folder.
3. Upload the .ipynb notebook to google colab (100% free)
4. Run the cells in order. Upload the unzipped .txt files when google prompts you to upload. The program should run without any problems!

If you do not wish to upload the notebook to google colab, you may also run it on VSCode, Pycharm, Jupyterlab, Anaconda, etc.
Simply follow steps 1 & 2 above, then open the .ipynb in your IDE of choice (be sure that it supports .ipynb files). 
**You will need to ensure that the .txt files are contained in the same directory as the .ipynb file.**
If this requirement is satisfied, you must simply comment out the lines in cell #3 (i.e. from google.colab import...), run the cells in order, and the file should run perfectly. 
If you receive an error, change the file opening line in the parse_corpora function in the 4th cell to reference the direct location of the folder that contains the .txt files: e.g.
```
  with open(f"{name}", 'r', encoding='utf-8') as file:
```
becomes:
```
  with open(f"C:/path/to/{name}", 'r', encoding='utf-8') as file:
```

Enjoy!
