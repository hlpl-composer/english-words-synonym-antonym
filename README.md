```
--------------------------------------------------------------------------------------------
Note. The zip file "hlpl_english_words_synonym_antonym.zip" must be extracted
in "hlpl_english_words_synonym_antonym/" directory before running installation
--------------------------------------------------------------------------------------------
```

# hlpl_english_words_synonym_antonym

hlpl_english_words_synonym_antonym lists english words synonyms and antonyms in a readable database python package

## Basic Usage: 

### Installation
This package can be installed from [PyPi](https://pypi.python.org/pypi/hlpl_english_words_synonym_antonym) by running:
```
pip install hlpl_english_words_synonym_antonym
```

### Command line: 

To get some info about the sofwtare, on console, execute the command line:
```
hlpl_english_words_synonym_antonym
```
To get the sofwtare version, on console, execute the command line:
```
hlpl_english_words_synonym_antonym version
```


### Basic usage: 

To return list of English words synonyms and antonyms tuplet, execute:
```
from hlpl_english_words_synonym_antonym import english_words_synonym_antonym
hlpl_list,conn=english_words_synonym_antonym.get()
```
```hlpl_list``` stands for words synonyms-antonyms list
```conn``` stands for database file connection

Each element (say `hlpl_list_x`) in the python tuplet `hlpl_list` has the properties:
```
hlpl_list_x[0]==word
hlpl_list_x[1]==word synonyms
hlpl_list_x[2]==word antonyms
```

### License
hlpl_english_words_synonym_antonym is licensed under the [MIT license](https://opensource.org/licenses/MIT).



<p style="font-size:19px;color:green;font-weight:bold;">Contributions are welcome! Please make a pull request.</p>

#### Development pattern for contributors

1. [Create a fork](https://help.github.com/articles/fork-a-repo/) of the [main hlpl_english_words_synonym_antonym repository](https://github.com/hlpl/english-words-synonym-antonym) on GitHub.
2. Make your changes in a branch named something different from `master`, e.g. create a new branch `my-pull-request`.
3. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/).

