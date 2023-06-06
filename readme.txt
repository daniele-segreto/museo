- Banner
Ho inserito sul Banner una freccia animata, in modo da direzionare l'utente verso il menù principale e la conseguente pagina da utilizzare. Sotto la scritta Museum ho inserito un'etichetta per pagina, in modo da distinguere le varie pagine (home, gallery, history, opere, contatti).

- Home
Sulla home ho inserito il tasto per visualizzare il dettaglio dell'articolo e di conseguenza, sulla pagina dell'articolo, ho inserito il tasto per tornare alla home.

- Footer
Sul footer ho inserito le icone dei social principali (facebook, twitter, instagram) e li ho resi cliccabili inserendo un target "_blank". Passando sul mouse, dunque all'hover, le icone iniziano a ruotare, facendo un giro su se stesse.

- Gallery
La sezione Gallery contiene alcune fotografie del museo, ho utilizzato onmouseover e onmouseout, manipolando l'opacità iniziale a 0.5 e al passaggio del mouse a 1.0.

- History
La sezione History contiene una Breve storia del museo e un Carosello interattivo.

- Opere
Sulla sezione Opere ho utilizzato JQuery UI per realizzare una tabella contenente alcune opere famose. L'utente può cambiare a suo piacimento l'immagine e la descrizione cliccando semplicemente sul titolo dell'opera (inserito sul tab).

- Contatti
La pagina contatti contiene un form sulla sinistra e una mappa (incorporata tramite API di Google Maps) sulla destra.

- Responsive
Ho utilizzato le classi container, row e col-lg-* di Bootstrap per creare un layout responsivo.
La classe container viene utilizzata come contenitore principale.
La classe row viene utilizzata per creare una riga e le classi col-lg-* per le colonne.
Ho utilizzato due @mediaQuery sul file CSS per gestire banner, footer, alcuni bordi e altre piccole sfaccettature sui dispositivi con larhezza massima 768px e 567px.