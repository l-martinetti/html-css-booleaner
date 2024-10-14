The Booleaner
===
## Esercizio
Data l'immagine di una pagina di riferimento, devo ricrearla in modo quanto più fedele possibile usando gli strumenti discussi a lezione rispetto ad HTML e CSS.

## Il mio approccio
Come sempre dò uno sguardo generale alla pagina che devo andare a ricreare, in questo mi concentro a dividere in 3 macrosezioni la pagina:

1. Come Header metto il riquadro con il logo "The Booleaner" e l'immagine che si ripete in orizzontale di sfondo.

1. Il main della pagina lo faccio cominciare con il titolo dell'argomento discusso che sarà il mio h1, subito sotto ho una scritta più piccola a cui andrò a modificare il colore sul CSS dandogli una classe specifica in quanto lo stesso colore viene ripetuto solo in fondo alla pagina, per la scritta The Booleaner potrei aggiungere una seconda classe con cui distinguerlo. 
Subito sotto ho due immagini una di fianco all'altra che posso iserire tramite due img, seguite sotto da due didascalie per cui penso di usare il font corsivo con il tag em. quanto detto fino ad ora sarà la mia prima sezione. La seconda sezione la individuo nella porzione di testo sopra l'elenco non ordinato e l'elenco in sè, così da poter gestire più facilemnte i diversi elementi presenti in pagina, nello specifico una parte evidenziata che gestiscon con un tag span che mi permette nel CSS di dare il colore sullo sfondo, subito dopo invece inserisco un elenco non ordinato. Non essendoci differenze sostanziali ne necessità apparenti, aggiungo nella seconda sezione anche la tabella e il testo subito sotto, in questo potrei anche facilitarmi nel CSS l'evidenziatura gialla selezionando il tag span come figlio del div che conterrà tutto e che quindi saranno solo quelle due porzioni di testo. La tabella richiederà probabilmente l'uso di diverse classi per alternare il colore dello sfondo, mentre per allineare il testo di ciascuna colonna con il titolo della stessa penso di usare una proprietà text-align justify, assicurandomi che la tabella ricopra tutto lo spazio orizzontale che è dispoibile.

1. Infine guardando al footer, avrò un titolo più piccolo a cui seguono due immagini. Come soluzione per metterle una sopra l'altra penso di usare due contenitori separati, due div che essendo elemnti blocco dovrebbero portarmi alla soluzione. l'immagine la metterò poi di sfondo sul CSS alla scritta che fa da titolo.

Adesso vediamo cosa succede!