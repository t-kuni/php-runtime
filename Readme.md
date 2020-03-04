# Download

```bash
wget -O __php-runtime.zip https://github.com/t-kuni/php-runtime/archive/master.zip \
  && unzip -d __php-runtime __php-runtime.zip \
  && mv __php-runtime/php-runtime-master/{__env,docker-compose.yml} ./ \
  && rm -rf __php-runtime __php-runtime.zip
```


```bash
echo '__env' > .git/info/exclude
echo 'docker-compose.yml' > .git/info/exclude
```

# Usage

```
docker-compose run php sh
```