# docker stratolinux/couchpotato

This is a Dockerfile to set up "CouchPotato" - (http://couchpota.to/)
Build from docker file
```
git clone https://github.com/tssgery/strato-couchpotato.git
cd strato-couchpotato
docker build -t couchpotato .
```
docker run -d -v /*your_config_location*:/config -v /*your_videos_location*:/videos -v /*your_download_location*:/downloads -p 5050:5050 couchpotato
