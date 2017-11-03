# Set up Raspberry Environment
## Prepare a MicroSD Card
- I bought a microSDZXC UHS-1 128GB Card from Samsung
- On Windows 10, right click the SD drive and quick format it. Must choose "NTFS"
- Download http://www.ridgecrop.demon.co.uk/guiformat.exe
- Run guiformat, and select the SD Drive. Click "Run" with default options
- Download Noobs from https://www.raspberrypi.org/downloads/noobs/. Select "Download Zip"
- Copy contents in NOOBS_v2_4_4 to the SD card

## Compile code
- kick off a console window
- Run: sudo apt-get install libssl1.0-dev
- Run:
```
sudo apt-get install build-essential unzip cmake mercurial \
uuid-dev libcurl4-openssl-dev liblua5.1-0-dev \
libgoogle-glog-dev libgtest-dev libpng-dev libjpeg-dev \
libsqlite3-dev libssl-dev zlib1g-dev libdcmtk2-dev \
libboost-all-dev libwrap0-dev libjsoncpp-dev libpugixml-dev
```
- If cmake runs into error, run:
```
rm -rf *
```

## Node JS
http://thisdavej.com/beginners-guide-to-installing-node-js-on-a-raspberry-pi/
- curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
- sudo apt install nodejs

