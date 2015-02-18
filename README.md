# ERP
Se almacenará todo el código del futuro ERP de OSEF

Una ves instalas GIT, debes configurarlo:

git config --global user.name "mtxosef"
git config --global user.email "osef@hotmail.com"

Generando tu Public Key:

ssh-keygen

Copias todo el texto:

get-content /Users/osef/.ssh/id_rsa.pub
type /Users/osef/.ssh/id_rsa.pub

Arrancando el proyect:

git init

Agregas tu archivo:

echo $null >> README2
git add README2

Verifica los archivos modificados en tu computadora:

git status

Agregas:

git commit -m "Test"

Copias lo del repositorio:

git remote add origin https://github.com/mtxosef/ERP.git
git pull origin master

Mandas al repositorio tus archivos:

git push origin master

Agregar ramas

git branch dev

Cambiarte de rama

git checkout dev
