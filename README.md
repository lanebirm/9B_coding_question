# 9B_coding_question

Repo for NineByte coding question. Provided question and test files found in to root of this repository.
tile-elit.pdf is the coding question.

## Dependencies 

Install the provided requirements.txt file with pip. Recommend using creating a virtual environment and installing to that. 
https://note.nkmk.me/en/python-pip-install-requirements/

## Setup:

To be able to run the python scripts with commands as outlined in the coding question objective a link in the systems local bin is needed.
This link can be setup and execution permisions with the following commands.

Ubuntu commands where $REPO_LOCATION = location of cloned repo. (Some commands may need to be run with sudo privileges depending on your system):
```
$ cd $REPO_LOCATION
$ chmod +x test_script
$ cd /usr/local/bin
$ ln -s $REPO_LOCATION/test_script .
$ cd $REPO_LOCATION
```