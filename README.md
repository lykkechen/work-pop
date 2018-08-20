# Girls Code It Workshop

## Obiettivo di oggi!

Realizzare un sito web da zero 😊
Questo è ció che vogliamo ottenere, date un'occhiata [qui](https://ladygaga-resume.netlify.com/) 😉


`
---
`

# Lezioni
Pregi di bulma bello e responsive
https://ladygaga-resume.netlify.com/

Importatante

Indentare    Option + shift + F

# 00-installazione
Obiettivo: creare un ambiente di lavoro

* Installa l’editor per scrivere codice
Ecco il [link](https://code.visualstudio.com)https://code.visualstudio.com
- Attiva il salvataggio automatico:
Apri Visual Studio Code > Clicca su File > Spunta l’opzione **salvataggio automatico**

# 01-prepara-il-tuo-progetto
- Crea una cartella vuota e chiamala `workshop-poplar`
- Apri **visual studio code** e apri la cartella con File > Apri…

[image:7CD9DA54-9F62-476D-8B2C-DF0D8765EE4A-6952-000039072CC92D97/Screen Shot 2018-08-12 at 21.37.02.png]

(Faccio screen sul cursore sul primo pulsante)

- Crea un file `index.html`
- Vai sul sito di [Bulma](https://bulma.io/documentation/overview/start/) e copia lo **Starter template** nel file `index.html` appena creato
- Vai nella cartella `workshop-poplar` e apri il file `index.html` con un browser
###### Come puoi vedere hai appena una pagina web :heart_eyes:


# 02-inizia-a-personalizzare-il-template
* Sostituisci nel tag `h1` `Hello World` con `Bio`
* Sostituisci il contenuto del tag `p` con una tua breve biografia
* Per vedere il risultato ricarica la pagina web sul browser

# 03-crea-un-altra-section
* Creare una nuova section con un container
* Crea un titolo con il tag `h1` e inserisci il tuo nome
* Crea un paragrafo con il tag `p`  con il tuo anno di nascita
* Crea un paragrafo con il tag `p`  con il luogo di nascita

# 04-aggiungi-le-prime-icone
- All'interno dei tag `p` inserisci l'elemento `icona` prendendo il codice dal sito di [Bulma](https://bulma.io/documentation/).
- Puoi trovare altre icone gratuite sul sito di [Fontawesome](https://fontawesome.com/icons?d=gallery&m=free).

# 05-aggiungi-la-tua-foto
- Scegli una tua immagine e copiala nella cartella del progetto.
- Cerca in [Bulma](https://bulma.io/documentation/) l'elemento che ti permette di aggiungere un'immagine
- Incolla l’elemento per l’immagine sopra il tag  `<h1 class="title">` 
- Cancella dalla classe `is-128x128` 
- Sostituisci l’interno di  `src="..."`  con il nome della tua immagine, compresa l’estensione (.png o .jpg)
- Ricarica la pagina per vedere il risultato

# 06-aggiungi-le-colonne
- Vai su [Bulma](https://bulma.io/documentation/) e cerca come inserire **2 colonne**

![Bulma columns](../assets/bulma-columns.gif)

- Copia le colonne subito sotto al `<div class="container">`
- Nella prima inserisci tutto il tag relativo all’immagine
- Nella seconda, inserisci il tuo nome e le icone col testo relative al tuo anno e luogo di nascita
- Ricarica la pagina per vedere il risultato 😍

### Proporzioni delle colonne

Come vedrai,  le colonne che hai aggiunto hanno la stessa dimensione: ognuna occupa metà dello schermo.

- Cerca su [Bulma](https://bulma.io/documentation/) le varie classi che si possono aggiungere alle colonne.
- Noi abbiamo impostato le proporzioni della prima colonna affinché sia di 1/3 e il testo di 2/3
- Sperimenta con le varie classi e poi osserva il risultato ricaricando la pagina del browser 😍


# 07-aggiungi-una-sezione-colorata
- [Bulma](https://bulma.io/documentation/) possiede delle sezioni colorate che si chiamano `hero`
- Cerca su [Bulma](https://bulma.io/documentation/) come inserire un hero verde acqua
- Aggiungi l’hero in fondo, subito sotto alla `section` con la tua descrizione
- Rimuovi il contenuto del `<div class="container">`
- Aggiungi **3 colonne** della stessa dimensione
- In ogni colonna inserisci un `p` con un’icona
- Cerca su [Bulma](https://bulma.io/documentation/)  come modificare l’icona e renderla più grande
- Aggiungi sotto ad ogni icona un titolo con un aggettivo che ti rappresenta e un sottotitolo con una descrizione.

### Centra il contenuto delle colonne

- Aggiungi classe `has-text-centered` al container per centrare il contenuto di tutte le colonne

# 08-crea-section-per-esperienze
- Crea una nuova section con un title
- Cerca su [Bulma](https://bulma.io/documentation/) l’elemento media object
- Crea un media object
- Aggiungi un div con classe  `media-left` e al suo interno inserisci un’immagine
- Sostituisci la src dell’immagine, con una tua immagine salvata nella cartella
- Sotto al media-left aggiungi un `media-content` 
- All’interno del media-content crea un `div content` con all’interno titolo e descrizione dell’esperienza

Ora hai creato il primo elemento, se ne vuoi aggiungere altri ti basta copiare e sostituire il contenuto 😍

# 09-crea-una-sezione-contatti
- Crea un nuovo hero colorato
- Aggiungi un titolo per indicare che si tratta della sezione contatti
- Aggiungi degli anchor tag `<a href="..."> ... </a>`
- Inserisci all’interno dell’anchor tag l’icona di Facebook
- Inserisci all’interno di `href` il link al tuo profilo facebook

Se vuoi puoi aggiungere altri anchor tag e inserire gli altri collegamenti ad altri tuoi social 😍

## Personalizzare palette e font

## Creare account su netlify e deploy

## Next steps
- Configurazione dominio personalizzato (gratuito oppure a pagamento)
- Aggiungere nuove sezioni e un menu personalizzato
- Aggiungere page anchors e un menu personalizzato
- Aggiungere animazioni standard
- Aggiungere un video di youtube in una section
# Riunione: Organizzazione workshop
#girlscodeit

## Requisiti
Installare visual studio code, capire il concetto di file ed estensione, saper organizzare un progetto minimo e saper aprire una pagina web con il browser.

## Workshop
Obiettivi: imparare a creare la prima pagina HTML con Bulma + Fontawesome 5, capire la differenza tra tag/class/style e la struttura del DOM, caricare su netlify il proprio sito web.

## Workshop next
Obiettivi:


## Cose da fare
- prepare template per “chi sono”
- preparare lista di aggettivi per sezione 3 del workshop