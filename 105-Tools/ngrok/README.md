1.Download & install ngrok
https://ngrok.com/download
------------------------------
Be sure to download ngrok before anything else. Follow the instructions to make sure it's installed correctly. 

2.Connect your account 
https://dashboard.ngrok.com/get-started
-----------------------------------------
Running this command will add your account's authtoken to your ngrok.yml file. This will give you more features and all open tunnels will be listed here in the dashboard. 
--------------------------------------------------------------
./ngrok authtoken 2w1uhgVEvaoXMYF18pCT7_7xe9BuPUhzdUcQQ6jLgFs
--------------------------------------------------------------

3.Start your first tunnel

Once you have your local server or other program running, you can open a tunnel pointing to the port where it's currently running. If you're having trouble, read the documentation to explore other tunneling options.
---------------------
./ngrok http 80      |
---------------------
Free ngrok accounts receive a random URL each time a tunnel is started. Upgrade to a paid plan to reserve ngrok subdomains for only your account, set up custom CNAMEs, and more.
View and replay requests

4.Visit 
----------------------
http://localhost:4040 
-----------------------
anytime ngrok is running to see a history of requests on your tunnels. You can also inspect the headers and responses for each request, or replay a request to speed up your development process. 
