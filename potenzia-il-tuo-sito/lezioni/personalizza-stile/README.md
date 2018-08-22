# Personalizzare sito

Per poter modificare lo stile della pagina devi inserire nel tag `head` un tag `style`
Il tag `style` è il contenitore di tutti gli stili, per modificare ad esempio:
* grandezza, colore, stile dei font
* colore di sfondo
* animazioni
* e moltre altre cose
* 
Il linguaggio utilizzato nel tag style è chiamato **CSS**

## Modificare il font
* Vai su fonts.google.com che è una raccolta di font gratuiti che puoi utilizzare sul tuo sito.
* Clicca sul `+` in basso apparirà una tab `Family selected` con il font scelto
* Apri la tab e copia tutto il `link-href`
* Incollato nel tag `head`
* Crea all'interno del tag `head` un tag `style` e inserisci il selettore desiderato, questo farà in modo che le modifiche vengano applicate solo a quest'ultimo
Ad esempio, prova ad applicarlo a tutto il documento scrivendo:

```
<style>
    body  {
        font-family: 'Cardo', serif;
    }
</style>
```

Ecco un link dei altri possibili selettori https://www.w3schools.com/cssref/css_selectors.asp

* Ora puoi provare a sostituire a `body` il tag `h1`, come vedrai, solo il titolo avrà un font diverso


## Modifica lo sfondo

Per modificare solamente determinate sezioni invece che tutti gli **elementi** `section` puoi creare una tua **classe** personale,
ad esempio `class="mio-sfondo-verde"`

Aggiungi questa classe all'interno di una section in questo modo

`<section class="section mio-sfondo-verde >`

Ora definisci come deve essere `mio-sfondo-verde`  dentro il tag `style`

Ad esempio:

```
<style>
    .mio-sfondo-rosa  {
        background-color: lightseagreen;
    }
</style>
```

* Attenzione a mettere il punto davanti al nome della classe
* Possono essere inseriti anche colori nelle codifiche **HEX** _#000000_ e **rgb** _rgb(0,0,0)_

Puoi sperimentare con molte altre proprietà che puoi trovare qui https://cssreference.io/ 😍