# Installare Rasa

Scaricare:

- **Anaconda** e installarlo selezionando anche la spunta per aggiungerlo alle variabili di ambiente (serve a creare un enviroment virtuale pulito)

- **ngrok** (per poter comunicare con piattaforme di messagistica)

## Comandi per configurare Rasa su Windows

da terminale:

- conda create --name Rasa_es python==3.8

- conda activate Rasa_es

- conda install -c anaconda urllib3

- pip3 install -U pip3 --user

- pip3 install rasa


## Per altri sistemi operativi

Ci sono semplici guide sulla documentazione ufficiale Rasa (https://rasa.com/docs/rasa/installation/) o su youtube per configurare rasa anche su altri sistemi operativi ed è preferibile inizializzare Rasa in questo modo. 

Ma se ci dovessero essere particolari problemi a configurarlo potete scaricare VirtualBox (https://www.virtualbox.org/wiki/Downloads) e questa macchina virtuale Linux su cui c'è già una versione configurata di rasa al suo interno:

https://univpm-my.sharepoint.com/:f:/g/personal/s1106609_pm_univpm_it/EkKVwXswqV1NgSLW_ItT73UBC99ZnSXb9MIhRoEMyxH8OA?e=izvG5X

e aggiungerla a Virtualbox:

![Config new machine Virtual Box](https://user-images.githubusercontent.com/48383441/145264177-71c77bf0-f030-467b-8970-396699994e6e.PNG)


Avviata la macchina inserire il seguente comando sul suo terminale:

- pip3 intstall -U rasa

