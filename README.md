# searchpy

Search for files from terminal or from scripts 

#installation
sudo su
apt-get install git
git clone https://github.com/zer0c0d3/searchpy.git
cp searchpy/searchpy /usr/bin/seachpy
chmod +x /usr/bin/searchpy

#Usage
#With output file
searchpy -p [path for scan] -s [word to find] -o [outputfile]
#Only print
searchpy -p [path for scan] -s [word to find]
