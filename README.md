# vagrant
script vagrant

# initialisez  en utilisant une image ubuntu/trusty64
 vagrant init

# creer la ressource 
vagrant up

# voir les ressources parraport a un dossier
vagrant status

# voir l'ensemble des ressources
vagrant global-status 

# se connectez a une machine 
 vagrant ssh

# arretez un vm
 vagrant halt

# supprimer un vm
 vagrant destroy

# telechargez un box en donnant la version
  vagrant init ubuntu/trusty64 --box-version 'version'
# Packager notre box 
 vagrant package --output nginx.box  

