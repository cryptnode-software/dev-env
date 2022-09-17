FROM mysql:8.0.21

LABEL authors="Colton Nielsen"

ENV MYSQL_ALLOW_EMPTY_PASSWORD 1
ENV MYSQL_USER dev
ENV MYSQL_PASSWORD dev
ENV MYSQL_DATABASE dev

EXPOSE 3306

CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]
