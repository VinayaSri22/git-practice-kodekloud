**Question:**
The Nautilus development team has provided requirements to the DevOps team for a new application development project, specifically requesting the establishment of a Git repository. Follow the instructions below to create the Git repository on the Storage server in the Stratos DC:

1. Utilize yum to install the git package on the Storage Server.
2. Create a bare repository named /opt/news.git (ensure exact name usage).

**Solution:**
LogIn into Storage server
> ssh natasha@ststor01

> Password: Bl@kW

> sudo su -

> yum install git

> cd /opt/

> git --version

> git init --bare news.git

> ls news.git/

> exit
