# readmeWorkshop 📚
A little workshop explaining how readmes works, some tweaks and secrets just to make the learning easier and fun to apply in every day life. This is a guide on markdown as well

# Partiamo dalle basi.
Dobbiamo:
- [x] spiegarvi che cos'è un readme
- [x] Perché vi serve saperli scrivere
- [ ] Il fatto che i readme sono scritti in MarkDown
- [ ] Come scrivere un readme
- [ ] Piccoli concetti avanzati (immagini, gif e tabelle)

## Che cos'è un readme?
Beh **questo che state leggendo cos'è secondo voi?**, è proprio un readme già 🤯 il readme è quel file che ignorate e che non scrivete su github appena create una repository. Eh già vi guardo tutti so cosa fate e _come lo fate_ quindi non mentitemi dicendo "no ma io li faccio" non vi crederò.

## Perché vi serve saperli scrivere 🧠
Allora qui è molto importante, scrivere readme non solo vi aiuta a esporre il vostro progetto, visto che il readme è appunto la vostra **VETRINA** dei progetti, serve a mostrare all'utente che visita la vostra repository il contenuto in maniera testuale (e anche visuale) del vostro codice.
* _Se la vetrina è brutta o confusa il cliente non capirà in principio come c'è nel negozio._
* Risponde alla domanda → come uso questo progetto? A voi piacerebbe leggere macchina dei gelati e anziché avere scritto sopra come utilizzarla, vi dovete improvvisare ingegnieri? Immaginate qualcuno che non ha mai programmato nel vostro linguaggio, vede un progetto, app, script che ha un nome tipo "do this" e poi non sa come installarlo quali script far eseguire su riga di comando, la compatibilità del software e tanto altro.…
* Come funziona sto codice già? Se ti fai questa domanda davanti al tuo codice la risposta è **Sono fottuto**

Sono stato abbastanza suggestivo o volete altri esempi

### Forse uno dei motivi più importanti è proprio la costruzione del vostro portfolio
Eh già, oltre all'imagine profilo il vostro profilo è fornito di un readme di default, con cose scritte in maniera predefinita.
A voi interessa far capire che tipo di individuo siete, in più fa molto figo ✨


## Un po' di mk avanzato
| Colonna 1     | Colonna 2 (Centrata) | Colonna 3 (A destra) |
|---------------|:--------------------:|---------------------:|
| Ciao          |          Sono        |               Bello|
| Il Markdown   |         è            |             Potente|
|



| test  | test2 | test3 | test4 |
|---|---|---|---
|prova|figo|interessante| sorprendente|


### I code snippet
volete fare i fighi e avere il testo colorato a modi vscode? Così chi legge non si prende un accidenti perché non capisce manco come avete indentato il tutto?
Easy fate tre backtick (linux tastiera italiana = altgr + ?)
```cpp
//commenti

#include <stdio.h>

int main(int ac, char** av)
{
	//indentazione definita dal vostro file di testo
    std::cout<<"scrivo codice nel readme"<<std::endl;

    return (0);
}
```


