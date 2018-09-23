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
        proprietà: valore che indica come deve risultare
      }

3. Per aggiungere l'effetto all'icona, ti basta questa classe qui all'interno del tag `<style>`:
  > 
    .icon:hover {
      transform: scale(1.3);
    }

Questa proprietà ti permetterà di scegliere quanto deve ingrandirsi l'icona al passaggio del mouse.

Noi abbiamo inserito 1.3, ma ti consigliamo di provare altri valori e sperimentare 😊

![hover-scale](../assets/hover-scale.gif)