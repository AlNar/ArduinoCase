# Diario Arduino Case Nr. 1

| Luogo        | Data           |
| ------------- |:-------------:|
| Trevano      | 02.09.2016 |

## Lavori svolti
All'inizio abbiamo avuto una chiara spiegazione sui due moduli presenti in queste ore di progetti (Modulo 306 e Progetti) e un introduzione ai vari software (git) che andremo ad usare per l'organizzazione dei nostri progetti.
Il tutto con una durata complessiva di 2 ore occupando tutta la mattinata.
Nel pomeriggio abbiamo iniziato con la teoria base sul come usare git, dopodiché siamo partiti a creare l'account su GitHub, creare il progetto su di esso ed infine provare ad usare SourceTree.

## Problemi riscontrati / soluzioni
Abbiamo avuto un problema con SourceTree per via del proxy.
Lo abbiamo risolto creando un file .gitconfig nella cartella dell'utente corrente inserendo delle impostazioni.
```
[user]
  name = nome cognome
  email = nome.cognome@samtrevano.ch

[core]
  autocrlf = true
  #excludesfile = C:\Users\samt\Documents\gitignore_global.txt

[filter "lfs"]
  clean = git-lfs clean %f
  smudge = git-lfs smudge %f
  required = true

[http]
  proxy = http://nome.cognome:proxypass@proxy:8080

[https]
  proxy = https://nome.cognome:proxypass@proxy:8080
```
## Punto della situazione rispetto alla pianificazione

## Programma di massima per la prossima giornata
