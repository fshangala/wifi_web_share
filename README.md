# wifi_web_share
A file sharing environment where one computer acts as a server in the network and every other computer connected to the network can access the files through the web interface by entering the IP address of the host computer in the browser as url.
The web application is written in PHP and therefore requires a http server with PHP installed, alternatively you can just install XAMPP or WAMP server on the computer which is to act as a server.
With XAMPP server, you're able to upload to the application a maximum of 40MB data, you can change this by editing the phone.ini file on the server and set the variable max_upload_size=1000M to put the maximum as 1GB.
Once you run the server, transfer the folder of the wifi_web_share into the htdocs folder of your server.
Then Finally, to access the wifi_web_share from the server computer, simply enter the URL http://localhost/wifi_web_share into the browser.
To access it on a different computer on the same network simply enter the IP address of the server computer in the browser e.g http://192.168.43.65/wifi_web_share
