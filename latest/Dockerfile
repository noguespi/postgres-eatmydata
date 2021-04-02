FROM postgres:latest

RUN apt-get update && apt-get install -y eatmydata && apt-get clean

ENTRYPOINT ["eatmydata", "docker-entrypoint.sh"]

CMD ["postgres"]
