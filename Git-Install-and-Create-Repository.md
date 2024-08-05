**Question:**
The Nautilus development team shared with the DevOps team requirements for new application development, setting up a Git repository for that project. 
Create a Git repository on Storage server in Stratos DC as per details given below:
- Install git package using yum on Storage server.
- After that, create/init a git repository named /opt/apps.git (use the exact name as asked and make sure not to create a bare repository).

**Solution:**

1. ssh natasha@ststor01
2. sudo su -
3. yum install git
4. cd /opt/
5. git init apps.git
