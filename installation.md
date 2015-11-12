1- Lancer la machine virtuelle
2- Ouvrir un terminal :
	cd / //se rediriger vers la racine
	sudo chmod 777 home //se donner les droits sur le dossier home 
	cd home
	mkdir sites //creer le dossier sites
	cd sites
	touch readme.txt //creer le fichier readme
	
	sudo apt-get install jekyll //installation de l'application Jekyll
	jekyll new monsite
	cd monsite
	jekyll serve (dans un autre terminal)