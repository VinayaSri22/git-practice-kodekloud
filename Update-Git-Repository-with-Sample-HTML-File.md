**Question:**
The Nautilus development team has initiated a new project development, establishing various Git repositories to manage each project's source code. 
Recently, a repository named /opt/media.git was created. 
The team has provided a sample index.html file located on the jump host under the /tmp directory. 
This repository has been cloned to /usr/src/kodekloudrepos on the storage server in the Stratos DC.

1. Copy the sample index.html file from the jump host to the storage server placing it within the cloned repository at /usr/src/kodekloudrepos/media.
2. Add and commit the file to the repository.
3. Push the changes to the master branch.

**Solution:**
1. cd /tmp/
  scp index.html natasha@172.16.238.15:/usr/src/kodekloudrepos/media
  ssh natasha@ststor01 
  cd /usr/src/kodekloudrepos/media
  chmod 777 media/*
  git add .
  git commit -m "adding index.html"
  git push origin master
