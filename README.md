# SchedAutoShutdown

## English

### What it is

This XML configuration file for the Windows 10/11 Task Scheduler automatically shuts down the computer according to the following schedules:

* Monday to Friday at 2:00 PM and 11:00 PM;
* Saturday at 12:00 PM.

### How it works

It first runs a 5-minute countdown and then forcibly shuts down the computer using the following commands:

`timeout -t 300`

`shutdown -s -f -t 0`

### Other features

* Starts the task only if the computer has been idle for 10 minutes.
* Waits for 10 minutes of idle time.
* Stops the task if the computer is no longer idle.
* Restarts the task if the computer becomes idle again.
* Wakes the computer to run the task.
* Allows the task to be run on demand.
* Stops the task if it runs for more than 1 day.
* Forces the task to stop if it doesn’t stop when requested.

### How to install it

* Download the **SchedAutoShutdown.xml** file.
* Open the **Task Scheduler** in Windows 10/11.
* On the left side, click **Task Scheduler Library**.
* On the right side, right-click on an empty area.
* Select **Import Task**.
* Choose the **SchedAutoShutdown.xml** file.
* Click **Open**.

---

## Italian

### Cos'è

Questo file di configurazione in XML per l'Utilità di pianificazione di Windows 10/11 spegne il computer automaticamente in base alle pianificazioni:
- dal lunedì al venerdì alle 14:00 ed alle 23:00;
- il sabato alle 12:00.

### Come funziona

Prima esegue un conto alla rovescia di 5 minuti e poi spegne forzatamente il computer tramite i seguenti comandi:

`timeout -t 300`

`shutdown -s -f t 0`

### Altre funzioni

- Avvia l'attività solo se il computer è inattivo per 10 minuti.
- Attende l'inattività per 10 minuti.ù
- Interrompe l'attività se il computer non è più inattivo.
- Riavvia l'attività in caso di ripresa dello stato di inattività.
- Riattiva il computer per eseguire l'attività.
- Consente l'esecuzione dell'attività su richiesta.
- Interrompe l'attività se eseguita per oltre 1 giorno.
- Se l'attività non si ferma quando richiesto, impone l'interruzione.


### Come installarlo

- Scaricare il file **SchedAutoShutdown.xml**.
- Aprire l'**Utilità di pianficazione** in Windows 10/11.
- Sul lato sinistro cliccare su **Libreria Utilità di pianificazione**.
- Sul lato destro cliccare con il tasto destro in uno spazio vuoto.
- Selezionare **Importa attività**.
- Selezionare il file **SchedAutoShutdown.xml**.
- Cliccare su **Apri**.

