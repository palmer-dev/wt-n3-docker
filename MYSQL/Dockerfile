# Utilisez l'image MySQL officielle comme base
FROM mysql:latest

# Définissez les variables d'environnement
ENV MYSQL_ROOT_PASSWORD="P@sswordMySqlDocker"
ENV MYSQL_DATABASE="tp_docker_mysql"

# Exposez le port MySQL
EXPOSE 3306

# Redémarrez toujours le conteneur
CMD ["--default-authentication-plugin=caching_sha2_password"]
