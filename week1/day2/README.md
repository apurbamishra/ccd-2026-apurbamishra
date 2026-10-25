

\# CCD Week 1 Day 2 — Local Containerization



\## 1. Public Docker Hub Image



\*\*Docker Hub Repository:\*\*  

https://hub.docker.com/r/apurbamishra/my-web-app



\*\*Image Tag:\*\* `apurbamishra/my-web-app:v1`



\## 2. Docker Images



The following output shows the Docker images available on my laptop after completing the lab.



```text

IMAGE                        ID             DISK USAGE   CONTENT SIZE   EXTRA

alkimi/ccd-course:week1      c25d24c12b11       3.67GB          816MB    U

apurbamishra/my-web-app:v1   c7b7607d5539       83.9MB         20.4MB    U

hello-world:latest           11a3eb1597e8       25.9kB         9.49kB    U

my-web-app:v1                c7b7607d5539       83.9MB         20.4MB    U

```



\## 3. Project Files



\- `server.py` — Python HTTP server that displays container diagnostic information.

\- `Dockerfile` — Instructions used to build the Docker image.



\## 4. Local Testing



The microservice was tested in a web browser at:



http://localhost:8080



