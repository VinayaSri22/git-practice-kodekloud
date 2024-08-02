**Question:**
Nautilus developers are actively working on one of the project repositories, /usr/src/kodekloudrepos/official-t2q1. Recently, they decided to implement some new features in the application, and they want to maintain those new changes in a separate branch. Below are the requirements that have been shared with the DevOps team:


On Storage server in Stratos DC create a new branch xfusioncorp_official-t2q1 from master branch in /usr/src/kodekloudrepos/official-t2q1 git repo.

Please do not try to make any changes in the code.

Use below credentials to SSH into the storage server and to complete this task.

Username: sarah
Password: S3cure321

**Solution:**

1. ssh sarah@ststor01
2. sudo su -
3. cd /usr/src/kodekloudrepos/official-t2q1
4. git branch -a
5. git checkout -b xfusioncorp_official-t2q1
6. git branch -a