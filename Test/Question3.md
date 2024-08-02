**Question:**
Commit the change of file lion-and-mouse-t1q6.txt which is placed under /home/sarah/story-blog-t1q6 repository on Storage server, file is already staged. 
A commit records the change in the repository compared to its previous state. But before that we must configure the git user who will be the owner of the commit.

Set git username as sarah and user email as sarah@example.com using the below commands.

git config user.email sarah@example.com
git config user.name sarah

Use below credentials to SSH into the storage server and to complete this task.

Username: sarah
Password: S3cure321

**Solution:**

1. ssh sarah@ststor01
2. sudo su -
3. cd /home/sarah/story-blog-t1q6
4. git config user.email sarah@example.com
5. git config user.name sarah
6. git config --list
7. git status
8. git add .
9. git commit -m "Adding file"