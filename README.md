
###use in your Dockerfile
```sh
FROM mj1440/php-apache-innershift

RUN rm -rf index.php

COPY . .

RUN chmod 777 -R /app/
```

