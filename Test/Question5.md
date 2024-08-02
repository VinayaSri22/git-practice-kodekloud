**Question:**
A new repository named /usr/src/kodekloudrepos/official-t2q5 was created recently and some data was added in it. 
Now one of the developers wanted to use this repository further to add/update some data.


Checkout the master branch under repo /usr/src/kodekloudrepos/official-t2q5.

Use below credentials to SSH into the storage server and to complete this task.

Username: sarah
Password: S3cure321

**Solution:**

1. ssh sarah@ststor01
2. sudo su -
3. cd /usr/src/kodekloudrepos/official-t2q5
4. git branch -a
5. git checkout -b /usr/src/kodekloudrepos/official-t2q5
6. git checkout master
7. ls -a