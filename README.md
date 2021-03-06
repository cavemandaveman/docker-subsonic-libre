# Docker Subsonic Libre

## 

![alt text][docker] ![alt text][alpine] ![alt text][subsonic]

This is a lightweight docker image for Subsonic, built on top of [Alpine Linux].

It uses a [Libre] distribution of Subsonic, free of licensing checks.

Created with minimal and KISS principles, it contains only the parts necessary to run Subsonic, weighing in at just under 250MB.

| Software Stack       |
| :------------------: |
| Subsonic 5.3         |
| Apache Tomcat 8.0.32 |
| OpenJDK 1.8.0        |
| Alpine Linux 3.3     |


## How to use this image

```
docker pull cavemandaveman/subsonic-libre:latest
```

Run instructions can be found in the [wiki].


[docker]: http://i.imgur.com/UaMaGdW.png "Docker"
[alpine]: http://i.imgur.com/zzi5aY0.png "Alpine"
[subsonic]: http://i.imgur.com/AhNrCFS.png "Subsonic"
[Alpine Linux]: http://gliderlabs.viewdocs.io/docker-alpine/
[Libre]: https://github.com/EugeneKay/subsonic
[wiki]: https://github.com/cavemandaveman/docker-subsonic-libre/wiki/Running-the-Image
