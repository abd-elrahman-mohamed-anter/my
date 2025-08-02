New conf abdoo.conf and cat it and the port is 85
![1  ](image1.png.png)

Made a new html config and started nginx 
![  2 ](image2.png.png)

Start the web page 
![  3 ](image3.png.png)

New conf engali.conf and cat it and the port is 89
and changed the html file and started nginx
![  4 ](image4.png.png)

Running the web bage 
![  5 ](image5.png.png)

Processes and ports by netstat
![ 6 ](image6.png.png)

We need to make localhost:88/my/ works so we made a my file in /var/www and 
made a index.html inside it and made my.conf inside conf.d
![  7 ](image7.png.png)

Then we run the command curl 
![  8 ](image8.png.png)

This the output of localhost:88/my/
![ 9](image9.png.png)

