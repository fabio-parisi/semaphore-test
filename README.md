# Demo project for Semaphore UI

## configurare SemaphoreUI

dopo aver avviato il docker compose

creare un nuovo progetto (non tamplate).

### Key Store

Creare una nuova chiave con all'interno la password di ansible-vault

Se non presente creare la chiave None di tipo None

### Repository

Creare un nuovo repository con il nome del progetto e il percorso del repository git 
es. http://github.com/fabio-parisi/semaphore-test

### Inventory
Creare un nuovo inventory di tipo file con il percorso del file inventory (es. inventory/hosts) e il nome del file (es. hosts.yml) e il il collegamento al repository creato in precedenza
es. inventories/cp_prova_1/hosts.yml

###  Task Template
Creare un nuovo task template con il nome del progetto e il collegamento alla repository, all'inventory, al vault creati in precedenza. poi inserire il playbook da avviare (es. deploy.yml)
