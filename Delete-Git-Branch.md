**Question:**
The Nautilus developers are engaged in active development on one of the project repositories located at /usr/src/kodekloudrepos/official. 
During testing, several test branches were created, and now they require cleanup. Here are the requirements provided to the DevOps team:

On the Storage server in Stratos DC, delete a branch named xfusioncorp_official from the /usr/src/kodekloudrepos/official Git repository.

**Solution:**
1. ssh natasha@ststor01
2. sudo su -
3. cd /usr/src/kodekloudrepos/official
4. git branch -a
5. git checkout master
6. git branch -d xfusioncorp_official
7. git status
