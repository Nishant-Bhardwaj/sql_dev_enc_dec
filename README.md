# To use encryption:


* Command: 
  * java -jar sql-dev.jar --flag=encrypt --text=passw

* Response Example:
  * flag = encrypt 
  
    encrypted = MDEyMzQ1Njc4OWZ1bGxlcpTR8qaApmgnIOhCLJk5qVw=

# To use decryption:

* Command:
    * java -jar sql-dev.jar --flag=admin_decrypt --text=MDEyMzQ1Njc4OWZ1bGxlctir96N+J3ddKiR7+Oy/+zk=

* Response Example:
  * flag = admin_decrypt
  
    decrypted = passw

# SQL Query Functionality:


* java -jar sql-dev.jar --user=root --pass=MDEyMzQ1Njc4OWZ1bGxlcpTR8qaApmgnIOhCLJk5qVw= --conUrl=jdbc:mysql://localhost:3306/auth_db --driver=com.mysql.cj.jdbc.Driver --query="select * from users;"

-- pass >> password should be passed after encryption 

** Logs:

username = root
url = jdbc:mysql://localhost:3306/auth_db
driver = com.mysql.cj.jdbc.Driver
query = select * from users;

** CSV File will be created