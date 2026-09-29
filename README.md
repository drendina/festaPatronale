Ora il telecomando non si apre finché non scrivi la password giusta, con l'avviso "Password errata" se sbagli. Ho controllato solo la sintassi, non l'ho provato su dispositivi reali. La password non è scritta nel codice, ma c'è la sua impronta (un codice che non permette di risalire alla password) da incollare una volta sola.

Impostazione (una volta sola)

Carica il file su GitHub come index.html, così com'è.
Apri https://drendina.github.io/festaPatronale/#setup.
Scrivi la password che vuoi e premi "Genera impronta". Compare una riga tipo const HASH = "a1b2c3…";.
Copiala e sostituisci nel codice la riga const HASH = ""; (in cima allo script). Poi ricarica il file su GitHub.
Da quel momento apri la pagina normale e scrivi la password. Il telefono la ricorda finché non premi Esci.

Finché non incolli l'impronta, la pagina mostra "Password non ancora impostata".

Cosa succede ai clienti

Chi toglie #mobile dal link trova la schermata della password. Senza quella giusta non entra e non può digitare numeri.
Il link #mobile di sola visualizzazione continua a funzionare senza password.

Limite
Il file è pubblico e l'impronta è leggibile da chiunque. Una password lunga e non banale resta al sicuro, mentre una corta come "1234" si può ricavare con qualche tentativo. Scegli quindi una frase di almeno 10-12 caratteri.
