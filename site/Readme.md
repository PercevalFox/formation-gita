nano app.py 
> Colle le contenu

nano requirements.txt
> Colle le contenu

nano Dockerfile 
> Colle le contenu 

sudo docker build -t site .
> Build de l'image

sudo docker run -d -p 8000:8000 --name site-web site
> Run du container

sudo docker ps -a 
> pour valider que le container fonctionne

http://127.0.0.1:8000
> affichage du site web
