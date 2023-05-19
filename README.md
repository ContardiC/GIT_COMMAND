# Comandi Git

Questo file README fornisce una breve descrizione dei comandi di base di Git.

## Configurazione iniziale

1. `git init`: Inizializza una nuova repository Git nella directory corrente.
2. `git config`: Configura le impostazioni di Git come l'utente e l'indirizzo email.

## Gestione delle modifiche

1. `git add <file>`: Aggiunge un file specifico alla staging area per la successiva commit.
2. `git add .`: Aggiunge tutti i file modificati alla staging area.
3. `git status`: Mostra lo stato corrente della repository, inclusi i file modificati e quelli nella staging area.
4. `git diff`: Mostra le modifiche apportate ai file in modo dettagliato.
5. `git commit -m "<messaggio>"`: Esegue una commit delle modifiche nella staging area con un messaggio descrittivo.
6. `git rm <file>`: Rimuove un file dalla repository e dalla staging area.
7. `git mv <file_originale> <file_renominato>`: Rinomina un file nella repository e nella staging area.

## Sincronizzazione con repository remota

1. `git remote add origin <URL>`: Collega la repository locale a una repository remota.
2. `git push -u origin <branch>`: Carica i commit locali su una repository remota.
3. `git pull`: Aggiorna la repository locale con le ultime modifiche dalla repository remota.
4. `git clone <URL>`: Crea una copia locale di una repository remota.

## Branching e merging

1. `git branch`: Mostra l'elenco dei branch presenti nella repository.
2. `git branch <nome_branch>`: Crea un nuovo branch con il nome specificato.
3. `git checkout <nome_branch>`: Passa al branch specificato.
4. `git merge <branch>`: Unisce il branch specificato al branch corrente.
5. `git branch -d <nome_branch>`: Elimina il branch specificato.

## Storia e annullamento

1. `git log`: Mostra la cronologia delle commit.
2. `git reset <commit>`: Annulla le commit precedenti, mantenendo le modifiche nella staging area.
3. `git revert <commit>`: Crea una nuova commit che annulla le modifiche apportate dalla commit specificata.
4. `git checkout -- <file>`: Ripristina un file alle sue ultime modifiche commit.

Questi sono solo alcuni dei comandi più comuni di Git. Consulta la documentazione ufficiale di Git per ulteriori informazioni sui comandi e le loro opzioni.

Happy coding!
