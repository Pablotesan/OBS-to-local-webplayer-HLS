# OBS-to-local-webplayer-HLS
Stream video using OBS to a local webpage.

(Having Docker and Docker-Compose installed is needed.)


---

If you pretend to run it under a domain name with ssl:

Check the general version:

[OBS-to-webplayer-HLS](https://github.com/Pablotesan/OBS-to-webplayer-HLS)

---

Steps:
1. Set up the webpage:

    - Use Docker:

      ```docker-compose up -d```

2. Configure OBS. 
    - Steps [here](https://obsproject.com/forum/resources/how-to-do-hls-streaming-in-obs-open-broadcast-studio.945/).

    - Set as output folder, the "video" one.

3. Go to "[http://localhost:80](http://localhost:80)" and enjoy.
