# Hands on Lab

## 0) Prerequisiti

Git for Windows installato nel proprio PC.

Un po' di dimestichezza con interfacce a riga di comando.

Un [account GitHub](https://github.com/join).

## 1) Clonare un repo esistente.

Dopo aver svolto questo esercizio sarete in grado di scaricare (clonare) un repository di un progetto che vi interessa.

1. Navigare nella pagina di un progetto di vostro interesse. Es.: [https://github.com/phenixita/helloWorld](https://github.com/phenixita/helloWorld).

1. Prendere l'URL per il clone dal pulsante `Clone or download`.

1. Aprire una sessione Powershell.

1. Eseguire il comando `git clone <URL>`. Questo comando scarica nella cartella `<nome progetto>` un repo di esempio col sorgente di un'applicazione Hello World in C#.

1. Eseguire `cd <nome progetto>` per entrare nella directory del progetto.

1. Eseguire `dir` per elencare il contenuto della directory.

## 2) Creare un repo nuovo su GitHub per un progetto esistente

Questo tutorial spiega come importare su GitHub un progetto già esistente in locale nel PC.

1. Creare nel proprio PC una nuova cartella con dentro un progetto (non importa che sia .Net).

1. Seguire [questa guida](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository) per creare un nuovo repository. **IMPORTANTE saltare il punto 6, 7 e 9**.

1. Seguire [questo link](https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line) per importare su GitHub una cartella con un progetto esistente dal passo 2. Invece che git bash si può utilizzare Powershell.

## 3) Aggiornare un repository

1. Aprire una sessione di PowerShell in radice del progetto.

1. Modificare del contenuto nei file del progetto a piacere.

1. Eseguire `git add .`.

1. Eseguire `git commit -m 'modifiche'`.

1. Eseguire `git push`.

1. Aggiornare la pagina del browser del vostro repo per vedere i nuovi contenuti.

## 4) Collaborare

1. Clonare il repo di un amico

1. Fork

1. Branch

1. Lavoro

1. Pull-request