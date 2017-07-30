# Contribuire al FIUP

:+1::tada:Innanzi tutto, grazie per dedicare del tempo a contribuire! :tada::+1:

Le seguenti sono delle regole per contribuire al FIUP e ai progetti correlati, ospitati nell'[Organizzazione FIUP](https://github.com/fiup) su GitHub.

Queste regole comuni vengono applicate per ciascun repository dell'organizzazione ma possono essere facilmente estese o adattate. Assicurati sempre di dare un'occhiata al file CONTRIB.md del singolo repository.

Per agevolare la creazione dei file CONTRIB abbiamo creato un [template facilmente adattabile](https://github.com/fiup/Getting_Started/docs/SAMPLE_CONTRIB.md) da includere in tutti i repository.

Se avete suggerimenti su come migliorare queste norme, sentitevi liberi di proporre cambiamenti a questo documento tramite pull request. 

#### Indice dei contenuti

[FIUP](#fiup)

[Codice di Condotta](#codice-di-condotta)

[Non voglio leggere tutta questa roba, ho solo una domanda!!!](#non-voglio-leggere-tutta-questa-roba-ho-solo-una-domanda)

[Come posso contribuire?](#come-posso-contribuire)
  * [Lavorare sui Repository](#lavorare-sui-repository)
  * [Segnalare Bug](#segnalare-bug)
  * [Suggerire miglioramenti](#suggerire-miglioramenti)
  * [Il tuo primo contributo](#il-tuo-primo-contributo)
  * [Pull Requests](#pull-requests)
  * [Altri tipi di Contributo](#altri-tipi-di-contributo)

[Stili](#Stili)
  * [Messaggi Git Commit](#messaggi-git-commit)
  * [Stile del codice](#stile-del-codice)
  * [Stile della documentazione](#stile-della-documentazione)

[Note Aggiuntive](#note-aggiuntive)
  * [Etichette per le Issue e Pull Request](#etichette-per-le-issue-e-pull-request)

## FIUP 

Il FIUP (Futuri Informatici dell'Universita' di Padova) è un'organizzazione senza scopo di lucro aperta a studenti, docenti e personale dei corsi di Laurea Triennale e Magistrale in Informatica
presso la Scuola di Scienze dell'[Universita' degli Studi di Padova](https://www.unipd.it/). 
Al momento è solo un'organizzazione gestita prevalentemente da studenti volontari, non è un'associazione ufficialmente riconosciuta dall'università.

## Codice di Condotta
Tutti i progetti e gli spazi FIUP adottano lo stesso [Codice di Condotta - Patto del contributore](https://github.com/FIUP/Getting_Started/blob/master/CODE_OF_CONDUCT.md).
Partecipando al FIUP, dichiari implicitamente di accettare e aderire a questo Codice di Condotta.
Per favore segnalate comportamenti in violazione con il Codice di Condotta all'indirizzo [fiup.unipd@gmail.com](mailto:fiup.unipd@gmail.com).
## Non voglio leggere tutta questa roba, ho solo una domanda!!!

> **Nota:** __Per favore non aprire una issue se hai solo una domanda.__ Puoi trovare più facilmente una risposta usando le risorse elencate in seguito.

Per qualsiasi dubbio o domanda chiedi nel [gruppo telegram del FIUP](https://t.me/FIUPd) dove la comunità è più attiva e saprà esserti d'aiuto.

## Come posso contribuire?

Puoi contribuire ai repository su GitHub, alle attività online e offline del FIUP o semplicemente aiutando altri utenti e caricando i tuoi appunti. Per ulteriori informazioni consulta la sezione [Altri tipi di contributo](#altri-tipi-di-contributo)
### Lavorare sui repository

Quando intendi collaborare ad un progetto presente nell'organizzazione FIUP in Github, il modo migliore è:

1. Individuare il repository corretto
2. Clonare il repository, possibilemente via [SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) usando il comando `git clone link_del_repository`
3. Aggiungere le proprie modifiche
4. Inviare una [Pull Request](https://help.github.com/articles/about-pull-requests/) al repository originale.

Se la Pull Request verrà accettata da un manutentore, il tutto andrà a buon fine e il contributo sarà aggiunto.

### Segnalare Bug
Seguire queste linee guida aiuta i manutentori e la comunità a capire più facilmente il problema.

Prima di inviare una segnalazione sui bug, per favore
controlla [questa lista](#prima-di-inviare-una-segnalazione-sui-bug) in quanto potresti scoprire che non necessiti di segnarlo. Mentre stai creando una segnalazione, per favore [includi quanti più dettagli possibile](#come-invio-una-buona-segnalazione). Se vuoi, puoi usare [questo template](ISSUE_TEMPLATE.md) per strutturare le informazioni.

#### Prima di inviare una segnalazione sui bug

* ***Fai una ricerca tra le issue*** in modo da accertarti che il problema non sia già stato segnalato. Se lo è, aggiungi un commento alla issue esistente al posto di aprirne una nuova. 

Puoi segnalare bug utilizzando le [Issue di GitHub](https://guides.github.com/features/issues/) 
#### Come invio una buona segnalazione?

I bug sono tracciati usando le [issue di GitHub](https://guides.github.com/features/issues/). Dopo aver individuato un problema, apri una issue nel relativo repository, fornendo le seguenti informazioni.

Esponi il problema e includi il maggior numero di dettagli in modo da aiutare i manutentori a riprodurlo.

* **Usa un titolo chiaro e descrittivo** per la issue, identificando il problema.
* **Descrivi precisamente i passi per riprodurre il problema** con quanti più dettagli possibile. 
Quando spieghi i passi, **non dire solo cosa hai fatto, ma spiega come lo hai fatto**. Per esempio, se hai compilato un sorgente LaTeX, spiega se hai usato uno script o un IDE.

* **Fornisci esempi espliciti per riprodurre i passi**.
Puoi includere link a file o a progetti su GitHub, o copia incollare parti di codice in questi esempi. Se includi spezzoni di codice nelle issuem usa [i blocchi di codice in Markdown](https://help.github.com/articles/markdown-basics/#multiple-lines).

* **Descrivi il comportamento osservato dopo aver seguito i passi** specifica esattamente qual è il problema e il suo comportamento.

* **Spiega quale sarebbe il comportamento corretto secondo te e perché**

* **Includi screenshots** che mostrino e descrivano i passi seguiti e possano mostrare in modo chiaro il problema. 

* **Puoi riprodurre costantemente la issue?** Se non puoi, fornisci dettagli circa quanto spesso il problema capita e sotto quali condizioni solitamente succede. 

Includi dettagli sul tuo ambiente e sulla tua configurazione:

* **Qual è il nome e la versione del sistema operativo usato**?
* **Stai usando una macchina virtuale?** Se si, che software usi e che sistemi operativi usi sia per l'host che per il guest?

* **Quali altri software stai usando inerentemente il problema?** Spiega che compilatore usi, e le dipendenze adottate. 
## Suggerire miglioramenti

Questa sezione ti guiderà su come inviare suggerimenti per migliorare il FIUP e i progetti ad esso correlati. Seguire queste linee guida aiuta i manutentori e la comunità a capire il tuo suggerimento :pencil: e a collegarlo ad altri già esistenti :mag_right: .

Prima di creare suggerimenti, per favore controlla [questa lista](#prima-di-inviare-un-suggerimento) in quanto potresti scoprire di non aver bisogno di crearne uno nuovo. Quando suggerisci una miglioria, per favore [includi quanti più dettagli possibile](#come-posso-suggerire-una-miglioria). Per agevolarti abbiamo creato [un template](ISSUE_TEMPLATE.md).

#### Prima di inviare un suggerimento 

* ***Fai una ricerca tra le issue*** in modo da accertarti che il suggerimento non sia già stato posto. Se lo è, aggiungi un commento alla issue esistente al posto di aprirne una nuova. 
#### Come posso suggerire una miglioria?

I suggerimenti per migliorare sono tracciati usando le [issues di GitHub](https://guides.github.com/features/issues/). Quando hai le idee chiare sulla modifica da proporre, crea una issue sul repository adatto (per inviare suggerimenti generali usa [questo repository](https://github.com/FIUP/Getting_Started/) ) e fornisci le seguenti informazioni:

* **Usa un titolo chiaro e descrittivo** per la issue che identifica il suggerimento.
* **Fornisci una descrizione passo passo della miglioria** con quanti più dettagli possibile.
* **Fornisci esempi concreti a dimostrazione dei passi**. se devi includere codice in questi esempi, usa [i blocchi di codice in Markdown](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Descrivi il comportamento attuale** e **spiega quale comportamento vorresti** e perché.
* **Spiega perché questa miglioria sarebbe utile** per la maggior parte degli utenti.
### Il tuo primo contributo

Non sai dove iniziare a contribuire al FIUP? 

Unsure where to begin contributing to Atom? Potresti iniziare dalle issue etichettate come `beginner` e/o `help-wanted`:

* [Beginner issues][beginner] - issue che riguardano problemi semplici che richiedono un paio di linee di codice e un paio di test.
* [Help wanted issues][help-wanted] - issues un po' più impegnative delle `beginner`.

Entrambe le liste di issue sono ordinate in base al numero totale di commenti. Anche se non è perfetto, il numero di commenti è un misuratore ragionevole dell'impatto che una issue potrà avere.
### Pull Requests

* Compila il [template](PULL_REQUEST_TEMPLATE.md)
* Non includere i numeri delle issue nel titolo della PR
* Includi screenshots e/o  GIF animate nella tua PR se lo ritieni utile.
* Documenta il nuovo codice usando gli [Stili della documentazione](#stili-della-documentazione
)
### Altri tipi di contributo

Per contribuire al FIUP non è necessario essere programmatori esperti. Puoi contribuire in tanti altri modi ad esempio:

* Aiutando gli utenti, rispondendo ai loro dubbi o domande sui [canali social](https://github.com/FIUP/Getting_Started/blob/master/FIUP_Rules.md#il-fiup-nei-social) in particolare su telegram e facebook.
* Caricando appunti e altri file negli spazi cloud del FIUP. [Rispettando le regole definite qui](https://github.com/FIUP/Getting_Started/blob/master/MEGA_FAQ.md)
* Partecipare alle attività offline del FIUP
* Proporre idee e suggerimenti all'indirizzo [fiup.unipd@gmail.com](mailto:fiup.unipd@gmail.com) o secondo le modalità indicate nella sezione [Suggerire miglioramenti](#suggerire-miglioramenti).
* Candidarsi a manutentore dei repository, o per avere un ruolo attivo nella struttura del FIUP, compilando [questo form](http://fiup.space/collaboration/) o via mail all'indirizzo [fiup.unipd@gmail.com](mailto:fiup.unipd@gmail.com).

## Stili

### Messaggi Git Commit

### Stili del codice

### Stili della documentazione

## Note aggiuntive

### Etichette per le Issue e Pull Request

Questo documento è ispirato alle linee guida per contribuire al progetto [Atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md).

