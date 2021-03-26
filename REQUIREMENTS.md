Packages:

php8 with modules
php-pear
php8.0-dev


Run PHP as pi user
give pi powers without sudo password: pi ALL=(ALL) NOPASSWD: ALL




UNRAR:
mkdir /tmp/unrar;cd /tmp/unrar
wget https://www.rarlab.com/rar/unrar-5.5.0-arm.gz
gunzip unrar-5.5.0-arm.gz
sudo cp unrar-5.5.0-arm /usr/bin/unrar
sudo cp unrar-5.5.0-arm /usr/local/bin/unrar
cd ..
rm -rf unrar
sudo chmod +x /usr/bin/unrar
sudo chmod +x /usr/local/bin/unrar



UNZIP:
sudo apt-get install unzip php8.0-zip


PDF: 
sudo apt-get install pdftk
 sudo apt-get install php8.0-imagick imagemagick imagemagick-common
sudo sed -i '/disable ghostscript format types/,+6d' /etc/ImageMagick-6/policy.xml


