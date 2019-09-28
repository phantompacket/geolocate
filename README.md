# GEOLOCATE - IP Geolocation tool by Brandon Anderson
# Simple geolocator using curl, nc, jq, and pygmentize 


# EASY INSTALLATION INSTRUCTIONS:
git clone https://github.com/phantompacket/geolocate
cd geolocate
chmod +x install.sh
./install.sh


# MANUAL INSTALLATION INSTRUCTIONS:
git clone https://github.com/phantompacket/geolocate
cd geolocate
apt-get install jq && pip install pygments
chmod +x geolocate
cp geolocate /usr/bin
