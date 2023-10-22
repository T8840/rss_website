# FreshRSS



## Use Docker Deploy

```
docker run -d --restart unless-stopped --log-opt max-size=10m    -p 80:80  -e TZ=Europe/Paris  -e CRON_MIN=*/1  -v freshrss_data:/var/www/FreshRSS/data  -v freshrss_extensions:/var/www/FreshRSS/extensions  --name freshrss   freshrss/freshrss
```


## Doc
[Page](https://freshrss.org/)
[GitHub](https://github.com/FreshRSS/FreshRSS)

