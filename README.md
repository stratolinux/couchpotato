# docker couchpotato
This is a Dockerfile to set up "CouchPotato" - (http://couchpota.to/)
Build from docker file
```
git clone https://github.com/tssgery/strato-couchpotato.git
cd strato-couchpotato
docker build -t couchpotato .
```
docker run -d -v /*your_config_location*:/config -v /*your_videos_location*:/videos -p 8085:8085 couchpotato
