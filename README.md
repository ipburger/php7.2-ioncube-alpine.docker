# php7.1-ioncube.docker

php7.1, apache and ioncube.

Based on [webdevops/php-apache:alpine](http://dockerfile.readthedocs.io/en/latest/content/DockerImages/dockerfiles/php-apache.html)

## usage

```
docker run -v <webroot>:/app -p 80:80 -p 443:443 ipburger/php7.0-ioncube
```

Customization and docs: [webdevops/php-apache:alpine](http://dockerfile.readthedocs.io/en/latest/content/DockerImages/dockerfiles/php-apache.html)
