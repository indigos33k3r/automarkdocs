# AutoMarkDocs

generate markdown docs from your python code automatically

combine with python-markdown for deploying to github pages right away!

files are imported and objects inspected, no source code parsing is done

# usage

    pip install pydoc-mardown
    
    cd /your/project
    git clone autmarkdocs 
    python autmarkdocs/automarkdocs.py
    pydocmd  build/serve/gh-deploy
    
# TODO

package and doc how to use args