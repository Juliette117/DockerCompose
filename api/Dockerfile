# Image
FROM python

# Repo de travail
WORKDIR /app

# Port exposé **COTE CONTENEUR**
EXPOSE 5000

# Copie des éléments du répertoire courant dans le répertoire de travail
COPY . /app

# Installe les dépendances
RUN pip install -r requirements.txt

# Commande à exécuter au démarrage du conteneur
CMD ["flask run --host=[0.0.0.0]"]