FROM php:8.2-cli

# Устанавливаем необходимые пакеты
RUN apt-get update && apt-get install -y \
    git \
    unzip \
    && docker-php-ext-install pdo pdo_mysql

WORKDIR /data/mysite.local

# Добавляем бесконечную команду
CMD ["php", "-a"]
