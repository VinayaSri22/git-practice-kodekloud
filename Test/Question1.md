**Question:**
Sarah created a new file named notes-t1q9.txt under /home/sarah/story-blog-t1q9 repository where she plans to write down ideas about the story for personal purposes. 
She does not want git to track this file or share it with her team mates.

It is good that the file is untracked. But it is still under GIT's radar. If you run the git add . command, accidentally git will start to track this file.


Let's configure git to ignore this file permanently.

Use below credentials to SSH into the storage server and to complete this task.

Username: sarah
Password: S3cure321

**Solution:**

1. ssh sarah@ststor01
2. sudo su -
3. cd /home/sarah/story-blog-t1q9
4. ls -a
5. touch .gitignore
6. vi .gitignore 
7. git status
8. git add .
9. git commit -m "Adding .gitignore file"
