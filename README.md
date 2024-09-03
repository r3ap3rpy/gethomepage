### Welcome

This repository holds my [gethomepage.dev](https://gethomepage.dev/latest/) configuration that is hosted on the [RaspberryPi5](https://thepihut.com/products/raspberry-pi-5).


You need to make sure you have the appropriate folder structure.

``` bash
root@raspberrypi:/opt/gethomepage# tree -L 1 .
.
├── compose
├── config
├── icons
├── images
└── README.md
```

After this you navigate to the **compose** folder and issue the **docker compose up -d** command, the **port:80** will be exposed.

![homepage](/images/homepage.png)


