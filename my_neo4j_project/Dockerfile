# Utilisez une image de base Python
FROM python:3.11

# Copiez le contenu de votre répertoire local dans le conteneur
COPY . /app

# Définissez le répertoire de travail à l'intérieur du conteneur
WORKDIR /app

# Installez les dépendances Python du projet
RUN pip install -r requirements.txt

# Commande pour exécuter votre application
CMD ["python", "app.py"]
