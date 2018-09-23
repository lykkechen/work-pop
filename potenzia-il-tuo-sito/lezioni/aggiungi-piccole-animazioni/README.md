# Aggiungi-piccole-animazioni

## Obiettivo: 
Aggiungere delle piccole e semplici animazioni all'interno del sito


# Ingrandimento icona al passaggio del mouse

Creare un'animazione che viene attivata al passaggio del mouse, può aiutare a mettere in risalto gli elementi cliccabili.

Per fare in modo che un elemento si ingrandisca quando ci passi sopra con il mouse, puoi aggiungere un effetto che viene attivato quando c'è un `hover`

1. Come prima cosa aggiungi un tag all'interno dell'**head** della tua pagina

2. Ora puoi scrivere la tua classe, seguendo questa struttura:
  >
      .nome-classe:hover {
        proprietà: valore che indica la quanto deve ingrandirsi
      }

3. Per aggiungere l'effetto all'icona, ti basta questa classe qui all'interno del tag `<style>`:
  > 
    .icon:hover {
      transform: scale(1.3);
    }

Questa proprietà ti permetterà di scegliere quanto deve ingrandirsi l'icona al passaggio del mouse.

Noi abbiamo inserito 1.3, ma ti consigliamo di provare altri valori e sperimentare 😊

![hover-scale](../../assets/hover-scale.gif)

---

# Cambio colore al passaggio del mouse

L'**hover** può essere utilizzato con altre proprietà, oltre allo scaling (ovvero ingrandimento)

1. Sostituisci il contenuto della classe `.icon:hover {}` con questa nuova proprietà:
   > 
    .icon:hover {
      color: black;
    }

Se ora proverai a passare sopra l'icona, noterai che cambierà colore 😊

![hover-color](../../assets/hover-color.gif)


# Aggiungere l'effetto soltando ad alcuni elementi

Aggiungendo l'hover alla classe `.icon`, avrai notato che adesso tutte quante le icone del tuo sito avranno lo stesso effetto, questo perché l'effetto della classe di stile `.icon:hover` viene applicato su tutti gli elementi che hanno la classe **icon**.

Se desideri che soltanto alcune icone cambino colore, allora dovrai creare una nuova classe e aggiungerla solo agli elementi che vuoi che abbiano l'effetto.

Ad esempio:

```
.cambia-colore:hover {
  color: red;
}
```