# Utiliser une image de base pour Logstash
FROM docker.elastic.co/logstash/logstash:7.14.0

# Copier le fichier de configuration de Logstash
COPY logstash.conf /usr/share/logstash/pipeline/

# Exposer le port pour Kibana
EXPOSE 5601

