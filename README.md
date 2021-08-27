## Germany COVID virtual assistant

[This](Corona_mit_Sprache_Irina.ipynb) is a dialog system that answers questions related to the covid situation in Germany (number of vaccinations and recovered people).
It uses the API from Robert Koch Institut. The two python files [file_update_recovered](file_update_recovered.py) and [file_update_vaccinations](file_update_vaccinations.py) extract and update the API data every time you run the program.
The code is also linked with [Eliza](eliza.py) so that the dialog system replies also when the user doesn't ask questions related to covid. The phrases used by Eliza are [here](deutsch.txt).
The dialog system uses also the program [EmoRec](emorec.py) for recognizing the user's emotions and replies accordingly.

**How to use it:**
<ul>
<li>in a terminal open "Corona_mit_Sprache_Irina.ipynb" with a Notebook IDE (eg  Jupyter Notebook or Google Collab)</li>
<li>run all</li>
<li>ask your questions</li>
</ul>

**Installation**

You need to install [Jupyter Notebook](https://jupyter.org/install), [emodb](http://emodb.bilderbar.info/docu/) and a code editor, for example [Visual Studio Code](https://code.visualstudio.com/download).

**Author**: Irina Anghelescu 
