# dbdiagrams
code generator for dbdiagrams.io from postgres


### Setup
Requirements: python3, pandas, psycopg2


### Usage
- Update the database connection string and output filepath in settings.conf
- Run ./generate_code
- Copy the generated code from the output file and visit dbdiagram.io [website](https://dbdiagram.io/d), once on the diagram page - paste it onto the code panel on the left. This should generate the diagram, make sure all the info is as desired - specially the references/table relationships. 
- You can screenshot the diagram and save image file !
