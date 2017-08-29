FROM redis

COPY root /

RUN chmod 777 /var/log/redis/redis.log
RUN mkdir -p /var/lib/redis

EXPOSE 6379
CMD ["redis-server", "/etc/redis/redis.conf"]



