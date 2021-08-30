## Germany COVID virtual assistant

[This](Corona_mit_Sprache_Irina.ipynb) is a dialog system that answers questions related to the covid situation in Germany (number of vaccinations and recovered people).
It uses the API from Robert Koch Institut. The two python files [file_update_recovered](file_update_recovered.py) and [file_update_vaccinations](file_update_vaccinations.py) extract and update the API data every time you run the program.
The code is also linked to [Eliza](eliza.py), so that the dialog system replies also when the user doesn't ask questions related to covid. The phrases used by Eliza are [here](deutsch.txt).
The dialog system uses also the program [EmoRec](emorec.py) for recognizing the user's emotions and replies accordingly.

**How to use it:**
<ul>
<li>download and install the program Emodb</li>   
<li>save the pytyhon files and the text file for Eliza to your computer</li>  
<li>in a terminal open "Corona_mit_Sprache_Irina.ipynb" with a Notebook IDE (eg  Jupyter Notebook or Google Collab)</li>
<li>make sure you are in the right directory before running the program and change the paths for the files that are used in the code (with the folder from your computer where you saved them)</li>
<li>for the function speech recognition, you need to create a business Google Cloud Account: https://cloud.google.com/speech-to-text/docs/quickstart-ui </li>  
<li>follow the steps and save the credentials to your computer</li>  
<li>change the path of the credentials in the code</li>  
<li>run all</li>
<li>ask your questions</li>
</ul>

**Installation**

[Jupyter Notebook](https://jupyter.org/install); [emodb](http://emodb.bilderbar.info/docu/)
**Author**: Irina Anghelescu 
