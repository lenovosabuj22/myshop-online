# myshop-online
myshop-online is a online based shopping 

Install Anaconda and Atom .
Install platformio-ide-terminal in Atom . To do so , settings>install>serach package name > install.
Install django using cmd : pip install django ==1.8.6 
Create and activate environment . 
Open anaconda prompt .
Then cmd : 
          conda create -n your_env_name //need only once 
          activate your_env_name // need every time when you open project // for linux use: source activate your_env_name
  The project here : https://github.com/lenovosabuj22/myshop-online?fbclid=IwAR3WC-CudhUyxcpTNHSuuxEZk0jNmO2ToETW-NAg2cKMeb23xwhD4LU3x_g
  
 Then go to the project path . 
 And then go to project dirctory through cmd:
                                cd Project 
                                cd myshop
 Or you can do it by opening atom on the project folder .
 Then just run:
                         python manage.py runserver
 Then a url will be generated like : http://127.0.0.1:8000/ or http://127.0.0.1:8000 80
 
 If any error then delete 'paypal.standard.ipn' and 'paypal' from myshop>settings : installed apps
                         
  
          
          
