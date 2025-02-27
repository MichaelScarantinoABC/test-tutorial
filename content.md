# Installare il plug-in di Finder OPTA in CODESYS

## Panoramica

CODESYS è uno dei principali ambienti di sviluppo per PLC e consente di
programmare Finder OPTA con linguaggi standard, come LD e ST.

Per programmare Finder OPTA utilizzando CODESYS, è necessario installare il
plug-in ufficiale. Questo tutorial guida all'installazione del plug-in in pochi
semplici passi.

## Obiettivi

- Scaricare ed installare il plug-in OPTA Configurator.
- Verificare il corretto funzionamento di OPTA CODESYS all'interno
  dell'ambiente di sviluppo CODESYS.

## Requisiti

Prima di iniziare, assicurati di avere:

- [PLC Finder OPTA CODESYS](https://opta.findernet.com/it/codesys) (x1)
- Cavo USB-C (x1)
- Ambiente di sviluppo CODESYS installato. Lo puoi scaricare [a questo
  link](https://opta.findernet.com/it/codesys#download-software).
- Plug-in OPTA Configurator. Lo puoi scaricare [a questo
  link](https://opta.findernet.com/it/codesys#download-software).

## Istruzioni

### Installazione del plug-in

Dopo aver scaricato il plug-in OPTA Configurator, estrai il contenuto
dell’archivio compresso. Il file estratto si chiamerà `OPTA_Configurator`.

![OPTA Configurator](assets/file.png)

Apri CODESYS e dal menu _Tools_, seleziona _CODESYS Installer..._:

![Apri CODESYS Installer](assets/launch_installer.png)

Lascia CODESYS Installer aperto e chiudi CODESYS:

![Chiudi CODESYS](assets/exit_codesys.png)

Ora, nel CODESYS Installer, fai clic sul pulsante _Install File(s)_:

![Installa file](assets/install_file.png)

Seleziona il file `OPTA_Configurator` che hai estratto in precedenza:

![Seleziona file](assets/package.png)

Dopo aver selezionato il file, apparirà una schermata di conferma. Fai clic su
_OK_, autorizza CODESYS ad apportare modifiche al sistema:

![Conferma installazione](assets/package_confirm.png)

Attendi il completamento dell'installazione:

![Progresso installazione](assets/installation_progress.png)

Al termine dell'installazione, verrà visualizzato un messaggio di successo:

![Successo installazione](assets/installation_success.png)

Per verificare che il plug-in sia stato installato correttamente, controlla
l’elenco dei componenti installati: tra questi dovresti trovare OPTA
Configurator.