# Xiaomi Vacuum Packeges
<img src="https://github.com/calas80/Xiaomi-Vacuum-Package/blob/master/Atemprima.PNG" alt="Anteprima">



Custom Component necessari:
  - vertical-stack-in-card
  - fold-entity-row
  - multiple-entity-row
  - button-card

# Spiegazioni
Questo packages è molto articolato. Comprende funzioni che probabilmente a molti di voi non serviranno e quindi potrete eliminare.
Vi spiego le cose "meno consuete" che rischiate di non capire:
- Pulizia Bagno Gatti:
  E' una funzione che manda una pulizia automatica ogni 3 ore per far pulire il robot nella stanza in cui si trova; senza avvisi e senza alterare nessun contatore. Visto che il mio bagno dei gatti è piccolo, il robot finisce la puliza dopo 3 minuti e viene mandato a casa.
- Richiesta Pulizie:
Visto che ho una bambina piccola, non è sempre un bene se le pulizie automatiche programmate partano senza chiedere il permesso, perchè potrebbero svegliare la piccola che dorme. Ho implemetato questa funzinoe, che se attiva, prima di partire con le pulizie chede conferma tramite una action. E' possibile programmare 2 richeste distinte a due orari diversi per ogni giorno della settimana. Se le richieste sono attive e non viene data risposta, le pulize automatiche non avvegono. Se il serbatoio del vacuum risulta pieno o se nessuno è in casa, la richiesta non viene fatta.
- Consumabili:
Il packages ha dei sensori interattivi per i filtri e i pezzi diricambio. Manderà un avviso quando stanno per esaurirsi.
- Serbatoio: Alla fine di ogni ciclo di puliza, il serbatoio verrà considerato pieno e verrà inviata una notifica per ricordarsi di svuotarlo. Per evitare danni, nessuna operazione di pulizia automatica avviene se il serbatoio risulta pieno.
Ci sono tre modi di svuotare il serbatorio:
  1 - Cliccare sull'immagine sbuota il serbatio (che appare solo quando il serbatoio è pieno)
  2 - Ho previsto una automazione grazie all'utilizzo di un sesonre di vibrazione Xiaomi che ho posizionato sul coperchio del robottino; quando il coperchio viene aperto per più di 8 secondi, il serbatoio viene considerato svuotato.
  3 - Programmare una routine di Alexa Grazie allo scritp corrispondete.
<img src="https://github.com/calas80/Xiaomi-Vacuum-Package/blob/master/Atemprima2.PNG" alt="Anteprima">
# Calendario
Ogni giorno è programmabile e attivabile singolarmente. Il tasto in alto "Pulizia Giornaliera" invece, disabilita le pulize automatiche senza dover modificare la programmazione settimanale.

# Funzioni speciali
il robottino torna alla base da solo in caso di errore o perdinta della mappa

# Impostazioni
Tutto (o quasi) quello che dovete impostare indicato con delle XXX, vi basta cercarle nel testo per trovare cosa dovete sotituire.
In linea di massima dovrete correggere i settaggi del vostro Vacuum e i notify.XXXX.


