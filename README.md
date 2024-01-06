# How to copy data from one machine to another on the same network.

**Run this docker image:**

```shell
docker run -d -p 8080:80 --name my-http-server \
  -v /Users/manindersingh/Downloads/http-server/uploads:/uploads \
  filebrowser/filebrowser

```

**Default username and password is:**

```shell
username: admin
password: admin

```

![Alt Text](ima/img.png)

**Now check the IP address of the machine on which you are running this image**
```shell
For instance: I am running this image on my mac and want to copy data from my window machine so in this case,
I need IP address of my mac because I want to hit the URL of http server which is running on my mac.

```
![Alt Text](ima/img.png)

```shell
This example, I am using from mac so that's why using localhost but you need to put your mac IP address if you are accessing from
some another machine.

```
![Alt Text](ima/img_1.png)


