# NGIMGPROXY

NginX + ImgProxy on Docker

# HOW TO USE

- Step 1 : create `.env` file with secret key and salt (see here : https://docs.imgproxy.net/#/configuration?id=url-signature)

```
IMGPROXY_KEY=
IMGPROXY_SALT=
IMGPROXY_PATH_PREFIX=
```

- Step 2 : run docker-compose

```
$ sudo docker-compose up -d
```

- Step 3 : Add firewall run that allows only your load balancer

ENJOY!
