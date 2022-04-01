# po_sqlite_db

find the database file at:

/iplant/home/travis_simmons/po_database/op.db


tables schema:

rgb  
full season uploaded  
primary keys: plant_name, date  
  
flir  
full season uploaded  
primary keys: plant_name, date  
  
scanner3d  
one date uploaded  
    - need to download each date and aggrigate  
primary keys: plant_name, date  
  
psii  
(not added yet)  

# File Description
po5.db has field_book with no duplicates & primary keys are set as plot and plant_name -> file that creates them is add_field_book.ipynb
po7.db has rgb cleaned -> edit_rgb.ipynb
po8.db has scanner3d cleaned
po9.db has psii edited
po10.db has flir edited
