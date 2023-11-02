# Utilisez l'image MySQL officielle comme base
FROM mysql:latest

# Définissez les variables d'environnement
ENV MYSQL_DATABASE=exampledb
ENV MYSQL_USER=exampleuser
ENV MYSQL_PASSWORD=examplepass
ENV MYSQL_RANDOM_ROOT_PASSWORD=1

# Exposez le port MySQL
EXPOSE 3306

# Redémarrez toujours le conteneur
CMD ["--default-authentication-plugin=caching_sha2_password"]
