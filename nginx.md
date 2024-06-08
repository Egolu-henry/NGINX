
# How to Set Up an Nginx Web Server in Ubuntu Virtual Machine Using Vagrant

1. `the first step required is to set up your server and doing the basic necessary things such as assigning the ip addr and bringing the machine up using the command vagrant up and ssh into the server using vagrant ssh `

2. ` update the server and install nginx with the command shown below `

![mkdir](/update%20packages.PNG)

![mkdir](/install%20nginx.PNG)

3. `install git  `

![mkdir](/install%20git.PNG)

4. ` check fot the status of the nginx and the ip addr of the machine `

![mkdir](/ip%20a.PNG)

5. ` start and enable the nginx using the sudo systemctl start nginx and enable the nginx using the sudo systemctl enable nginx `

6. ` git repository cloning `

![mkdir](/var%20clone.PNG)

7. `enable the appriopriate permissions `

![mkdir](/ownership.PNG)

![mkdir](/verify%20site.PNG)


8. `create a new nginx and modify the root and the server name`

![mkdir](/nano1.PNG)

9. ` paste the following lines modifying the server name and the root folder `

![mkdir](/nano2.PNG)

10. ` create a symbolic link to enable the site using the command below`

![mkdir](/symbolic%20link.PNG)

11. ` test the nginx congig for syntax errors using`

![mkdir](/test%20symbolic.PNG)

12. `Reload nginx to apply changes using sudo systemctl reload nginx`

13. `paste the domain name or the ip addr in the browser to view the result `

![mkdir](/hosted%20page.PNG)








