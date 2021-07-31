FROM php:7.4-apache

#tzdataのインスト Linuxシステムなどで使用されるタイムゾーンのデータ集 xdebug デバッグ　libpq-devはDB系かな
RUN apt-get update && apt-get install -y \
tzdata \
&& pecl install xdebug \
&& rm -rf /var/lib/apt/lists/*

#タイムゾーンの環境変数
ENV TZ=Asia/Tokyo
