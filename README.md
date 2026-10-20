Raffaele Cattaneo 5^C
comandi utilizzati per git bash repo:
cd desktop
mkdir cattaneo_raffaele_20261020
cd cattaneo_raffaele_20261020
git init                                                inizzializza la cartella come repo, rendondo possibile usare i comandi git ecc..
git add .                                               aggiunge i cambiamenti fatti alla repo
git commit -m "comento"                                 prepara e fotografa i cambiamenti fatti alla repo
git push                                                manda i cambiamenti della repo su git hub
git config user.name "username"                         firma della cartella
git config user.email "mail"                            firma della cartella
gh auth login                                           utilizzando per fare login su git hub e collegare la repository
gh repo create nomeRepo --public --source=. --push      crea la repository su git hub, ha bisogno di almeno un commit per essere usato il comando
gh auth log out                                         utilizzato per fare logout dal prorpio accoubt git hub