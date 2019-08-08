# dbdiagrams
code generator for dbdiagram.io from postgres


### setup
required : python3
```bash
sudo apt-get install libpq-dev python-dev 
pip install -r requirements.txt
```

recommended - use python virtual environment :
```bash
python -m venv env
source /env/bin/activate
```
Then follow the above setup steps


### generating the code
- update the database connection string and output filepath in settings.conf
- run ./generate_code
- copy the generated code from the output file and visit dbdiagram.io [website](https://dbdiagram.io/d), once on the diagram page - paste it onto the code panel on the left. This should generate the diagram, make sure all the info is as desired - specially the references/table relationships. 
- you can screenshot the diagram and save image file or you can create an account if you like the tool (i've no affiliation) !
