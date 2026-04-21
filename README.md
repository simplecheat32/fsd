# Usage : 
( will need mysql 8 , tomcat 10 and java 21 )
( "cd" command is used to navigate to a folder in terminal)
(if u keep mysql password as "admin123" then no need to change password in code files and compile them again for that u ned to open mysql terminal and enter this command : 
"  ALTER USER 'root'@'localhost' IDENTIFIED BY 'admin123'; ")

# 1 : in cmd :
cd fsd1

edit in the code : name etc.

python -m http.server 81

then in browser : localhost:81 


# 2 : in cmd :

cd fsd2

python -m http.server 82

then in browser : localhost:82


# 3 : in cmd 

cd fsd3

java LambdaOperations


# 4 :  

setup and open mysql client terminal

show databases;  ( for checking is "college" names db already exists else " create database college;")

use college;

show tables; ( check if "students" table already exists else "create table students;")

truncate students;

open cmd 

cd fsd4

edit sql password in code file

javac -cp ".;mysql-connector-j-9.6.0.jar" StudentCRUD.java

java -cp ".;mysql-connector-j-9.6.0.jar" StudentCRUD


# 5 : 

setup and open mysql client 

show databases; ( check if "company" db already exists else "create database company;")

use company;

show tables; ( check if "employee" table already exists else "create table employee;")

truncate employee;

in cmd 

cd fsd5

javac -cp ".;mysql-connector-j-9.6.0.jar" EmployeeCRUD.java

java -cp ".;mysql-connector-j-9.6.0.jar" EmployeeCRUD


# 6 : 

install and setup tomcat 10 

in file manager open fsd6 folder

copy WebApp folder

in file manager navigate to C:\apache-tomcat-10.1.52\webapps

paste the WebApp folder 

navigate to C:\apache-tomcat-10.1.52\bin

double click the "startup.bat" file 

open browser : localhost:8080/WebApp


# 7 : 

install and setup tomcat 10 

in file manager open fsd7 folder

copy fsd7 folder itself

in file manager navigate to C:\apache-tomcat-10.1.52\webapps

paste the fsd7 folder 

navigate to C:\apache-tomcat-10.1.52\bin

double click the "startup.bat" file 

open browser : localhost:8080/fsd7


# 8 :

install and setup tomcat 10 

in file manager open fsd8 folder

copy fsd8 folder itself

in file manager navigate to C:\apache-tomcat-10.1.52\webapps

paste the fsd8 folder 

navigate to C:\apache-tomcat-10.1.52\bin

double click the "startup.bat" file 

open browser : localhost:8080/fsd8


# 9 : 

install and setup tomcat 10 

in file manager open fsd9 folder

copy fsd9 folder itself

in file manager navigate to C:\apache-tomcat-10.1.52\webapps

paste the fsd9 folder 

navigate to C:\apache-tomcat-10.1.52\bin

double click the "startup.bat" file 

open browser : localhost:8080/fsd9


# 10 : 

in cmd 

cd fsd10

python -m http.server 83

in browser : localhost:83 


# 11 :

setup mysql client 

show databases; ( check is "studentdb" db exists else "create database studentdb;")

use studentdb;

show tables; ( check if "students" table exists else "create table students;")

from file manager edit the mysql password in code files in fsd11/src

in cmd 

cd fsd11

javac -cp "lib/" -d bin src/.java or javac -cp ".;lib/" -d bin src/.java

java -cp ".;bin;lib/*" StudentDAO


# 12 :

in cmd 

cd fsd12

java -cp "bin;lib/*" MainApp ( if doesn't work then first compile : "javac -cp "lib/*" -d bin src/*.java


# 13 :

open mysql client
show databases; (check if "studentdb" database exists else "create database studentdb;")
use studentdb;
show tables; (check if "product" table exists else "create table product;")
truncate product;
in cmd 
in file manager
open fsd13
u will find one more folder named "fsd13" in main "fsd13" folder 
copy the *SECOND* fsd13 folder 
navigate to C:\apache-tomcat-10.1.52\webapps
paste the fsd13 folder 
navigate to C:\apache-tomcat-10.1.52\bin
double click the "startup.bat" file
in browser : localhost:8080/fsd13/form

# 14 : 
in cmd 
cd fsd14
cd before
python -m http.server 85
in browser : localhost:85 
right click -> inspect -> click "network" section 
back to cmd
ctrl+c
cd ..
cd after 
python -m  http.server 86
in browser : localhost:86 
right click -> inspect -> click "network" section 
back to cmd -> ctrl+c

# 15 :
in cmd 
cd fsd15
java MainApp






