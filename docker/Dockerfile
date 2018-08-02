FROM concourseglobal/docker-img-django:develop

COPY . /usr/local/src/api-app

WORKDIR /usr/local/src/api-app

# The port that the gunicorn web application is running
EXPOSE 80

ENTRYPOINT ["bin/entrypoint.sh"]

CMD ["bin/dj-run.sh", "80"]
