**Question:**
The developers are adding some content under new repositories. There was some data added under /home/sarah/story-blog-t1q8 repository on the storage server. 
Commit the files that are currently in the staging area under this repository.

First check the status of the file using the command git status. Then commit using the commit message as Added the lion and mouse story

Use below credentials to SSH into the storage server and to complete this task.

Username: sarah
Password: S3cure321

**Solution:**

1. ssh sarah@ststor01
2. sudo su -
3. cd /home/sarah/story-blog-t1q8
4. git status
5. git add .
6. git commit -m "Added the lion and mouse story"
7.  git status
