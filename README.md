# Description :

Image resizing program

### Install Python :

If you don't have Python 3, please visit : https://www.python.org/downloads/ to download it !

### Virtual Environment :

#### Create a virtual environment in the project root :

    python -m venv env

#### Activate a virtual environment :

##### windows :

    env/Scripts/activate
    
##### linux/mac :

    source env/bin/activate
    
#### Install dependencies :

    pip install -r requirements.txt

## Run the program :

    py resize.py [-h HELP] [-p PATH] [-np NEWPATH] [-w WIDTH] [-ht HEIGHT] [-v VERBOSITY]

#### Arguments :

-  -p --path : the path to the file
-  -np --newpath : the new path to the file (optional, same path as the original image path if omitted)
-  -w --width : the desired image width
-  -h --height : the desired image height
-  -v --verbosity : increase output verbosity
