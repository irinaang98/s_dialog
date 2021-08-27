[This](Corona_mit_Sprache_Irina.ipynb) is a dialog system that answers questions related to the covid situation in Germany (number of vaccinations and recovered people).
It uses the API from Robert Koch Institut, the two python files [file_update_recovered](file_update_recovered.py) and [file_update_vaccinations](file_update_vaccinations.py) are extract the data and update it every time you run the program.
The code is also linked with [Eliza](eliza.py) so that the dialog system replies also when the user doesn't ask questions related to covid. The phrases used by Eliza are [here](deutsch.txt).
The dialog system uses also the program [EmoRec](emorec.py) for recognizing the user's emotions and replies accordingly.

