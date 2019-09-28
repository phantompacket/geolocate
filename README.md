# GEOLOCATE - IP Geolocation tool by Brandon Anderson
# Simple geolocator using curl, nc, jq, and pygmentize. 
#
#
# Requirements: curl, nc, jq, pygments
#
#
# EASY INSTALLATION INSTRUCTIONS:
# git clone https://github.com/phantompacket/geolocate
# cd geolocate
# chmod +x install.sh
# ./install.sh
#
#
# MANUAL INSTALLATION INSTRUCTIONS:
# git clone https://github.com/phantompacket/geolocate
# cd geolocate
# apt-get install jq && pip install pygments
# chmod +x geolocate
# cp geolocate /usr/bin
# OPTIONAL: python -m pip install requirements.txt     #INSTALL 'pygments' USING PYTHON2
# OPTIONAL: python3 -m pip install requirements.txt    #INSTALL 'pygments' USING PYTHON3
#
#
# HOW TO USE:
# Once the installation has finished, you can run the geolocate command from any directory.
# Use the geolocate command by itself to get information on your own Public IP.
# You can geolocate any IP address by typing is as a command-line argument after the geolocate command.
# 
# EXAMPLE:
# geolocate
# OR
# geolocate 216.58.193.206

