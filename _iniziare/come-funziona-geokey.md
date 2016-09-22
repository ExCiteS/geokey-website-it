---
layout: iniziare
title: "Come funziona GeoKey"
---

Questa è una introduzione ai i concetti di base di GeoKey. Fornisce un quadro più ampio sui diversi componenti e il modo in cui sono collegate.

Progetti, categorie e gruppi di utenti sono i componenti di base in GeoKey. Insieme, essi definiscono quali dati vengono raccolti e chi sarà in grado di accederli.

### Progetti

Le iniziative di Community Maps sono organizzati in progetti distinti. Ogni progetto ha un obiettivo specifico e di solito un'area geografica mirata; ad esempio, un quartiere, un distretto, un municipio. Per esempio, si desidera mappare i luoghi di divertimento preferiti nella vostra zona, come parchi, pub, ristoranti e negozi locali - questo sarebbe il vostro progetto. Le misure della qualità dell'aria lungo una strada sarebbe un altro esempio.

### Categorie

Ogni progetto definisce un insieme di categorie, a seconda di quali dati volete mappare. Ad un livello molto generico, una categoria dice qualcosa sul soggetto dei contributi nella categoria. Nell'esempio precedente, servirebbe una categoria per i parchi, un altra per i pub, un altra per i ristoranti ed un altra per i negozi locali. Si potrebbe anche designare una categoria singola - luoghi di divertimento - per tutti i locali.

Le categorie hanno campi (fields) che definiscono quali informazioni devono essere fornite per ogni contributo della categoria. Per i ristoranti, questo potrebbe essere un nome, l'indirizzo, il numero di posti a sedere e il tipo di cucina. I campi sono i tipi di dati (ad esempio testo, numero o un elenco di opzioni), ed e anche possibile definirne i vincoli come un valore minimo e massimo o se fornire un valore per un campo è obbligatorio.

Ogni volta che un utente crea un nuovo o contributo o aggiorna un contributo esistente, i dati forniti vengono convalidata con le definizioni dei campi di questo tipo di contributo.

### Gruppi utenti

Attraverso i gruppi di utenti si può assegnare ruoli ai membri di un progetto. In GeoKey ci sono quattro diversi livelli di ruoli utente:

1. **Administrators** (amministratori): Gli amministratori possono accedere a tutti i dati di un progetto, possono moderare e contribuire e così gestire il progetto. Possono creare e modificare le categorie ed i loro campi, creare o cambiare i gruppi di utenti, inclusa l'aggiunta e la rimozione di utenti e concedere le autorizzazioni a gruppi di utenti.
2. **Moderators** (moderatori) I moderatori possono moderare tutti i dati che sono autorizzati ad accedere. Ciò include la modifica o la rimozione dei contributi, commenti e file multimediali, nonché di approvazione contributi in sospeso. I moderatori possono ulteriormente contribuire al progetto.
3. **Contributors** (contributori): I collaboratori possono contribuire ad un progetto e leggere tutti i dati che sono autorizzati ad accedere. Essi possono modificare e cancellare i loro contributi, commenti e file multimediali.
4. ***Read only users*** (solo lettura): Gli utenti readonly (solo lettura) possono soltanto accedere ai dati pubblici di un progetto.

### Accedere ai progetti e ai contributi

GeoKey consente la definizione di chi può accedere ai progetti e dati su un livello molto dettagliato. Ci sono due tipi di progetti: _public_ (pubblici) e _private_ (privati).

**Public projects** (progetti pubblici): Progetti pubblici possono essere consultati da tutti, a prescindere se l'utente è registrato e loggato o meno. Di conseguenza, tutti i dati in un progetto pubblico è visibile a tutto il mondo.

**Private projects** (progetti privati): Progetti privati ??consentono di limitare l'accesso a un gruppo selezionato di utenti. Solo gli utenti che sono registrati, loggati e membri di uno dei gruppi di utenti del progetto avranno accesso ad un progetto privato. Per impostazione predefinita, tutti i dati in un progetto privato è accessibile a tutti i membri di gruppi di utenti del progetto. Per ogni gruppo di utenti, è pero possibile limitare ulteriormente l'accesso ad un sottoinsieme di tutti i dati in un progetto, selezionando le categorie e, per ciascuna delle categorie selezionate, attraverso la definizione di filtri il sottoinsieme richiesto. Nel precedente esempio, si e stato deciso di usare una categoria luoghi di diverteminto, si potrebbe limitare l'accesso del gruppo di utenti "Bambini" a ristoranti, parchi e negozi, escludendo i pub.
