#Aggiungi-nuove-pagine

## Obiettivo: 
Creare un menù che permetta di accedere alle altre pagine del tuo sito.


## Step:

1. Crea un nuovo file che abbia l'estensione `.html`.
  * Questo file corrisponderà alla tua nuova pagina.
  * Ad esempio puoi creare una pagina `about.html`
  * Nel tuo file `.html` appena creato, copia il contenuto del file `index.html`
   
2. Ora puoi andare su [Bulma](https://bulma.io) e cercare il componente **Navbar menu**
3. Copialo e incolla la struttura come primo elemento del tag `body`
4. Dentro il `div class="navbar-menu"` inserisci un `div class="navbar-end"`
5. All'interno di quest'ultimo inserisci un `div class="navbar-item"` per ogni pagina diversa pagina che vuoi sul sito.
6. Dentro a questo inserisci un tag: 
  ```
    <a href="about.html">
      <h3>About</h3>
    </a>
  ```
  * All'interno di `href=""` inserisci il nome del file, inclusa l'estensione, che corrisponde all tua nuova pagina





Per far funzionare lo scroll fino alla sezione **bio**, inserisci dentro la section contente la bio un `<section class="section" id="bio">`

Per mantenere sempre visibile e in alto la navbar puoi fissarla utilizzando la classe di bulma `is-fixed-top`

`<nav class="navbar is-fixed-top">`