# Download

```bash
wget -O __php-runtime.zip https://github.com/t-kuni/php-runtime/archive/master.zip \
  && unzip -d __php-runtime __php-runtime.zip \
  && mv __php-runtime/php-runtime-master/{env,docker-compose.yml} ./ \
  && rm -rf __php-runtime __php-runtime.zip
```

# Usage

```
docker-compose run php sh
```