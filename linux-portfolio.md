# sample commands

# User Management
sudo useradd devuser
sudo passwd devuser
sudo usermod -aG developers devuser

# Package Installation
sudo dnf install git -y
sudo apt install nginx -y

# Service Management
sudo systemctl start nginx
sudo systemctl enable nginx

# Performance Checks
top
free -h
df -h
iostat
journalctl -xe
