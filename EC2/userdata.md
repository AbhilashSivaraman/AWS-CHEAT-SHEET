```bash

#!/bin/bash

# Update system
sudo yum update -y

# Install Apache (httpd) and Git
sudo yum install -y httpd git

# Start and enable Apache
sudo systemctl start httpd
sudo systemctl enable httpd

# Clone your repository into /tmp
cd /tmp
sudo git clone https://github.com/AbhilashSivaraman/MyWebsite.git

# Remove default Apache files
sudo rm -rf /var/www/html/*

# Copy website files to Apache's document root
sudo cp -r /tmp/MyWebsite/* /var/www/html/

# Set correct ownership and permissions
sudo chown -R apache:apache /var/www/html
sudo chmod -R 755 /var/www/html

# Restart Apache to apply changes
sudo systemctl restart httpd
```