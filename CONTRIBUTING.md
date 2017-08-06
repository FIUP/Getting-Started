# Contribuire al FIUP

:+1::tada:Innanzi tutto, grazie per dedicare del tempo a contribuire! :tada::+1:

Le seguenti sono delle regole e delle linee guida per contribuire al FIUP e ai progetti correlati, ospitati nell'[Organizzazione FIUP](https://github.com/fiup) su GitHub.

Queste regole comuni vengono applicate per ciascun repository dell'organizzazione ma possono essere facilmente estese o adattate al singolo. Assicurati sempre di dare un'occhiata al file CONTRIBUTNG.md del singolo repository, in quanto potrebbe includere informazioni aggiuntive.

Se avete suggerimenti su come migliorare queste norme e le linee guida associate, sentitevi liberi di proporre cambiamenti a questo documento tramite pull request. 

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
  * [Licenze usate](#licenze-usate)

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
#### Creare un nuovo repository

Per agevolare la creazione dei file CONTRIBUTING abbiamo creato dei template facilmente adattabili da includere in tutti i repository.

Per creare un nuovo repository:
* Crea un nuovo repository all'interno dell'organizzazione FIUP in GitHub
* Esegui un clone in locale del repositor, ypossibilemente via [SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) usando il comando `git clone link_del_repository`
* Copia la [cartella docs del repository Getting_Started](https://github.com/FIUP/Getting_Started/tree/master/docs) dentro alla directory principale del tuo repository.
* Adatta i template contenuti nella cartella docs in base alle esigenze del tuo repository, in particolare:
    - Imposta un README, usando il [README template](https://github.com/fiup/Getting_Started/docs/README_TEMPLATE.md).
    - E' sconsigliato modificare i file [ISSUE_TEMPLATE](https://github.com/FIUP/Getting_Started/blob/master/docs/ISSUE_TEMPLATE.md) e [PULL_REQUEST_TEMPLATE](https://github.com/FIUP/Getting_Started/blob/master/docs/PULL_REQUEST_TEMPLATE.md) in quanto potrebbero entrare in conflitto con le linee guida generali per contribuire.
    - Imposta il file CONTRIBUTING con le linee guida specifiche per contribuire al tuo repository, adattando il [CONTRIBUTING template](https://github.com/fiup/Getting_Started/docs/CONTRIBUTING_TEMPLATE.md).
    - Assicurati che nei file README e CONTRIBUTIG sia presente un link al nostro [Code of Conduct](https://github.com/FIUP/Getting_Started/blob/master/CODE_OF_CONDUCT.md). Creando un nuovo repository dichiari di accettare e di rispettare il nostro codice di condotta.
    - Assicurati di avere un file LICENSE che specifica la licenza del tuo repository. Cerca di usare licenze libere. I repository del FIUP senza licenze non sono da considerarsi software proprietario. Per ulteriori informazioni consulta la nostra [policy sulle licenze](#licenze-usate). 
* Effettua le modifiche che ritieni necessarie al tuo repository, fai una commit e una push
* Complimenti, il tuo repository è impostato e fa ora parte del FIUP.
#### Collaborare ad un repository esistente
Quando intendi collaborare ad un progetto presente nell'organizzazione FIUP in Github, il modo migliore è:

1. Individuare il repository corretto
2. Clonare il repository, possibilemente via [SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) usando il comando `git clone link_del_repository`
3. Aggiungere le proprie modifiche
4. Inviare una [Pull Request](https://help.github.com/articles/about-pull-requests/) al repository originale.

Se la Pull Request verrà accettata da un manutentore, il tutto andrà a buon fine e il contributo sarà aggiunto.

### Segnalare Bug
Seguire queste linee guida aiuta i manutentori e la comunità a capire più facilmente il problema.

Prima di inviare una segnalazione sui bug, per favore
controlla [questa lista](#prima-di-inviare-una-segnalazione-sui-bug) in quanto potresti scoprire che non necessiti di segnarlo. Mentre stai creando una segnalazione, per favore [includi quanti più dettagli possibile](#come-invio-una-buona-segnalazione). Puoi usare [questo template](docs/ISSUE_TEMPLATE.md) per strutturare le informazioni.

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

Prima di creare suggerimenti, per favore controlla [questa lista](#prima-di-inviare-un-suggerimento) in quanto potresti scoprire di non aver bisogno di crearne uno nuovo. Quando suggerisci una miglioria, per favore [includi quanti più dettagli possibile](#come-posso-suggerire-una-miglioria). Per agevolarti abbiamo creato [un template](docs/ISSUE_TEMPLATE.md).

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

* Compila il [template](docs/PULL_REQUEST_TEMPLATE.md)
* Non includere i numeri delle issue nel titolo della PR
* Includi screenshots e/o  GIF animate nella tua PR se lo ritieni utile.
* Documenta il nuovo codice usando gli [Stili della documentazione](#stili-della-documentazione
)
### Altri tipi di contributo

Per contribuire al FIUP non è necessario essere programmatori esperti. Puoi contribuire in tanti altri modi ad esempio:

* Aiutando gli utenti, rispondendo ai loro dubbi o domande sui [canali social](https://github.com/FIUP/Getting_Started/blob/master/FIUP_Rules.md#il-fiup-nei-social) in particolare su telegram e facebook.
* Caricando appunti e altri file negli spazi cloud del FIUP, [rispettando le regole definite qui].(https://github.com/FIUP/Getting_Started/blob/master/MEGA_FAQ.md)
* Partecipare alle attività offline del FIUP.
* Proporre idee e suggerimenti all'indirizzo [fiup.unipd@gmail.com](mailto:fiup.unipd@gmail.com) o secondo le modalità indicate nella sezione [Suggerire miglioramenti](#suggerire-miglioramenti).
* Candidarsi a manutentore dei repository, o per avere un ruolo attivo nella struttura del FIUP, compilando [questo form](http://fiup.space/collaboration/) o via mail all'indirizzo [fiup.unipd@gmail.com](mailto:fiup.unipd@gmail.com).

## Stili

### Messaggi Git Commit

* Usa messaggi chiari e descrittivi delle modifiche apportate ("Fatti cambiamenti vari" non è un buon messaggio)
* Usa preferibilmente la lingua inglese
* Scrivi i messaggi usando il presente e l'imperativo  ("Add feature" not "Added feature") ("Move cursor to..." not "Moves cursor to...")
* Limita la prima linea a 72 caratteri o meno
* Nelle linee successive [collega liberamente la commit alle issue e alle pull request](https://help.github.com/articles/closing-issues-using-keywords/) 

### Stili del codice
Uno stile del codice standard per molti progetti è essenziale. Per i progetti FIUP, _salvo quanto specificato nel file CONTRIBUTING dei singoli repository_, non si adotta uno stile standard. Questo permette a chiunque di partecipare liberamente senza troppi problemi.
L'importante è che:

* Il codice sia commentato (in italiano e/o in inglese). Il codice non commentato è scarsamente utile soprattutto se riguarda esercizi che hanno lo scopo di far capire i procedimenti svolti e le soluzioni adottate.

### Stili della documentazione

Anche per la documentazione non adottiamo uno standard preciso. I linguaggi da usare sono preferibilmente HTML, Markdown e LaTeX. 

I commenti al codice sono da intendersi come parte integrante della documentazione.

## Note aggiuntive
### Etichette per le Issue e Pull Request

Questa sezione lista le etichette che usiamo per aiutarci a tener traccia e gestire sia le issue che le pull request.
Molte etichette sono usate in tutti i repositori del FIUP, ma alcune sono specifice di questo repository.

[La ricerca di GitHub](https://help.github.com/articles/searching-issues/) rende facile usare le etichette per trovare gruppi di issue o pull request alle quali sei interessato. Per esempio, potresti essere interessato nelle [issue aperte di questo repository non ancora controllate](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+repo%3Afiup%2Fgetting_started+comments%3A0). Per aiutarti a trovare issue e pull request in modo più efficace, ti incoraggiamo a leggere [questo approfondimento sui filtri di ricerca](https://help.github.com/articles/searching-issues/), ti aiuterà a scrivere query più mirate.

Le etichette sono raggruppate in base al loro scopo, ma non è richiesto che ogni issue abbia un'etichetta per ciascun gruppo o che una issue non possa avere più di un'etichetta per gruppo.

Per favore, apri una issue in `fiup/Getting_Started` se hai suggerimenti per nuove etichette. Se noti che alcune etichette non sono presenti nei repository, apri una issue in quel repository.


#### Tipi di Issue e loro stato

| Nome dell'etichetta |  Descrizione |
| --- | --- |
| `enhancement`  | Richiesta di nuove feature / miglioramenti, invio di suggerimenti. |
| `bug`| Bug noti o segnalazioni circa possibili bug. |
| `question` | Domande inerenti l'organizzazione FIUP in GitHub. Per altri tipi di domande usare i gruppi social. |
| `feedback` | Richiesta di feedback in merito ad un progetto da parte della comunità.  |
| `help-wanted`  | I manutentori del FIUP apprezzerebbero aiuto dalla comunità nel risolvere queste issue. |
| `beginner`  | Issue poco complese adatte a chi contribuisce per le prime volte al FIUP. |
| `more-information-needed` | Più informazioni devono essere raccolte circa questo problema o richiesta di miglioramenti ad es. i passi per riprodurre il problema). |
| `blocked`  | Issue bloccate da altre issue. |
| `duplicate` | Issue che sono duplicati di altre, già create in precedenza. |
| `wontfix` | Il team del FIUP ha deciso di non fixare la issue per il momento per qualche ragione. |
| `invalid`  | Issue non valide (per es. per errori degli utenti). |
| `wrong-repo` | Issue aperta nel repository sbagliato. |

#### Categorie per temi

| Nome dell'etichetta | Descrizione |
| --- | --- |
| `windows` | Relative ai problemi su Windows. |
| `linux` | Relative ai problemi su Linux. |
| `mac` | Relative ai problemi su macOS / iOS. |
| `documentation` | Relative a problemi / migliorie alla documentazione. |
| `performance` | Relative alle performance. |
| `security` | Relative alla sicurezza |
| `ui` | Relative alle parti grafiche. |
| `api` | Relative alle API. |
| `crash` | Relative ai problemi che causano un crash. |
| `git` | Relative ai problemi con git (per es. problemi con i file `.gitignore`). |

### Etichette per le Pull Request

| Nome dell'etichetta | Descrizione
| --- |  --- |
| `work-in-progress` | Pull request sulle quali si sta ancora lavorando, ulteriori modifiche arriveranno in futuro.|
| `needs-review` | Pull requests che necessitano di essere controllate da manutentori del FIUP per aggiornare i progetti. |
| `under-review` | Pull request in fase di controllo da parte dei manutentori del FIUP. |
| `requires-changes` | Pull request che necessitano cambiamenti dopo essere state controllate, a seguito dei cambiamenti dovranno essere riviste di nuovo. |
| `needs-testing` | Pull request che richiedono test manuali.|
### Licenze usate
Tutto il materiale caricato sugli spazi FIUP, se non esplicitamente rilasciato dall'utente allgando una specifica licenza, è da intendersi rilasciato sotto licenze [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) se si tratta di appunti, esercitazioni, e opere per i quali l’utente che carica dispone dei diritti. Per il codice, salvo quanto diversamente indicato, si intende interamente rilasciato sotto licenza [GPLv3](http://katolaz.homeunix.net/gplv3/).

E’ possibile condividere materiale e codice usando licenze differenti, purché l'utente includa un file "LICENSE" riportante la licenza che desidera utilizzare oppure includa nel materiale stesso dei riferimenti alla licenza stessa. Per incentivare la condivisione e un miglioramento continuo è consigliato evitare licenze chiuse e proprietarie.

Se non si sa che licenza scegliere, si può consultare [questo strumento](https://choosealicense.com/), ulteriori informazioni su come associare una licenza ad un repository, possono essere [reperite qui](https://help.github.com/articles/licensing-a-repository/). 

### Ulteriori riferimenti

Questo documento è ispirato alle linee guida per contribuire al progetto [Atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md).

