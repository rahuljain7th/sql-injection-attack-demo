#Example of SQL Injection ATTACK code
=============

Common code for the Relational Databases and Full Stack Fundamentals courses



1. Install vagrant and virtual box
2. Change directory to the vagrant directory in git bash for windows
3.Run Vagrant up 
4.  you can run vagrant ssh to log in to your newly installed Linux VM!
5. run python forum.py in the shell.
6. if your port is started on 8000 type http://localhost:8000/
7. Add Some Post in the page.
8. After add few post add the below post into box.  
        ');delete from posts;--
9. All the post gets deleted.
10. Solution to SQl Injection attack. use tuple instead os string concat
 c.execute("INSERT into posts (content) VALUES (%s)" , (content,))