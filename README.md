# crud_assignment

# i have added virtual environment also
#Important comand to run our assignment , if it is not working:

1)create virtual envirinment
2)install django: pip install django
3)i have added data base also, if you do not want to keep existing data, then crate the data base{ using 1) python manage.py makemigrations
                                                                                                          2)python manage.py migrate
4)also create the superuser to access the database     
                                          1)python manage.py createsuperuser
                                          2)give some username: e.g. root
                                          3)give some email address or you can skip also this step
                                          4)give the password: e.g. root
                                          5)password (again): root
                                          6)Bypass password validation and create user anyway? [y/N]: give y and then press enter
                                          
                                          -----> it will display "superuser created successfully"
                                          
5) to run the project:
  python manage.py runserver
  
  -------------> it will display output like:
  
                   System check identified 1 issue (0 silenced).
                    August 18, 2021 - 22:29:14
                    Django version 3.2.6, using settings 'crudproject2.settings'
                    Starting development server at http://127.0.0.1:8000/
                    Quit the server with CTRL-BREAK.
                    
 6) to go the data base:
 
       ---->http://127.0.0.1:8000/admin
       ---> give username and password( e.g root and root)---> then you can see the data base 


                                                                                                          
