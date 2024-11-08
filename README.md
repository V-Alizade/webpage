***  In order to build the page:

sphinx-build pages _build -b dirhtm

- pages is the directory of the inputs or the content that we want to show on the webpage. It contains 'conf.py' and the 'index.rst' files which are the configuration and webpage content files respectively.
- _build is the output directory and you need to define a name for it, '_' in the name is to identify the files we create.
- -b selects the output type
- dirhtml is the output type 



*** In order to see the webpage: 
python -m http.server -d _build/

