# U5-D14

Git da Console


Aprire terminale e aprire la repository creata su github e clonarla
$ ls -> LISTARE I FILE NELLA WORKING STATION
$ git status -> STATO DELLA REPOSITORY
$ git add . -> AGGIUNGERE TUTTI I FILE ALLA STAGING AREA) $ git add <nome_file> -> AGGIUNGERE IL FILE SELEZIONATO ALLA STAGING AREA
$ git commit -m "" -> AGGIUNGERE I FILE DALLA STAGING AREA NELLA REPOSITOY LOCALE
$ git log -> STORICO DEI COMMIT
$ git branch -M -> CAMBIARE NOME AL BRANCH ($ git branch -M -> MODIFICA IL NOME DELLA BRANCH PRINCIPALE DA MASTER A MAIN)
$ git push --set-upstream origin main -> PRIMO PUSH CREA UPSTREAM VERSO CORRETTO BRANCH ED EFFETTUA IL PUSH) $ git push -> DOPO PRIMO PUSH CON UPSTREAM SI USA DIRETTAMENTE PUSH
$ git branch -> LISTA BRANCH
$ git branch <nome_branch> -> CREARE NUOVA BRANCH ($ git branch new-branch)
$ git checkout <nome_branch> -> PASSA ALLA BRANCH SELEZIONATA ($ git checkout new-branch)
$ git checkout main -> TORNO IN MAIN
$ git merge <nome_branch> -> EFFETTUA MERGE DELLA BRANCH SELEZIONATA SULLA BRANCH CORRENTE IN LOCALE, IN QUESTO CASO SU MAIN ( $ git merge new-branch)
$ git push -> PUBBLICA LE MODIFICA NELLA REPOSITORY REMOTA
$ git branch -d <nome_branch> -> ELIMINA LA BRANCH IN LOCALE) $ git push origin -d ELIMINA LA BRANCH IN REMOTO
$ git tag v1.0.0 -> AGGIUNGE TAG LIGHTWEIGHT
$ git tag -a v1.0.0 -m "added tag" -> AGGIUNGE TAG ANNOTATED
$ git tag -> LISTA TAGS
$ git push --tags -> PUSH DEI TAGS IN REMOTO
$ git remote -v -> CONTROLLA CONNESSIONE CON LA REPOSITORY REMOTA
