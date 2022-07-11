# frozenyogurtshop

#!/bin/bash

sudo yum install httpd git -y

git clone https://github.com/rajulucky812/frozenyogurtshop.git /var/www/html/

sudo systemctl start httpd

sudo systemctl enable httpd

![image](https://user-images.githubusercontent.com/97225776/170913556-2e76750b-568b-4001-a88d-1800774d1a87.png)
