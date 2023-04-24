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