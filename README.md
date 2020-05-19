# docker_project
in this IIEC session we came to learn alot about the doker from the begining to the advance level .i was my pleasure to have a mentor like mr vimal daga sir.  we came to learn alot of things about docker  its usecases networking and also its docker compose file in this Docker project I have took a joomala image of 3.0 version and the other is a maria db image 10.1 version and then i also attached the volume to the database so that if we relaunch or if os crash the data remains save and also used PAT to acces from outside world and in this i  also attaches the local drivers. the code which i used is used in the docker-compose.yml file and it will run after using docker-up command
# Code  
Here is the code of the docker-compose file
![code](https://user-images.githubusercontent.com/60362872/82315193-95a06280-99e8-11ea-8dc1-b35394684a60.PNG)
# Why Joomla?
Joomla is a free and open-source content management system (CMS) for publishing web content, developed by Open Source Matters, Inc. It is built on a model–view–controller web application framework that can be used independently of the CMS.

Joomla is written in PHP, uses object-oriented programming techniques (since version 1.5) and software design patterns, stores data in a MySQL, MS SQL (since version 2.5), or PostgreSQL (since version 3.0) database, and includes features such as page caching, RSS feeds, printable versions of pages, news flashes, blogs, search, and support for language internationalization.

Over 8,000 free and commercial extensions are available from the official Joomla Extensions Directory, and more are available from other sources. As of 2019, it was estimated to be the fourth most used content management system on the Internet, after WordPress and Drupal.
![](https://github.com/rish-abh-jain/docker_project/blob/master/joomla.PNG)

We Can Also configure changes and make our own site

![](https://github.com/rish-abh-jain/docker_project/blob/master/joom.PNG)
# WHY MARIADB ?
MariaDB is a community-developed, commercially supported fork of the MySQL relational database management system (RDBMS), intended to remain free and open-source software under the GNU General Public License. Development is led by some of the original developers of MySQL, who forked it due to concerns over its acquisition by Oracle Corporation in 2009.

MariaDB intended to maintain high compatibility with MySQL, ensuring a drop-in replacement capability with library binary parity and exact matching with MySQL APIs and commands. However, new features diverge more. It includes new storage engines like Aria, ColumnStore, and MyRocks.
![maria](https://user-images.githubusercontent.com/60362872/82317506-fc734b00-99eb-11ea-979a-5cadbffbba50.PNG)
