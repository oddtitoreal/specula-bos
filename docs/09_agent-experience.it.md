# Il BOS e l'Agent Experience

*Il layer valoriale che rende coerenti gli agenti AI del brand.*

---

## Il nuovo utente non ha occhi

Gli agenti AI sono ormai utenti di prodotti e servizi. Non vedono schermi, non hanno preferenze sui bordi arrotondati e non si emozionano per le animazioni. Analizzano informazioni strutturate, eseguono operazioni e completano compiti. La loro soddisfazione è binaria: il lavoro è stato fatto correttamente, oppure no.

Questo cambiamento — dall'utente umano all'agente AI come utente di primo livello — è ciò che Menno Cramer chiama **Agent Experience (AX)**. E introduce un problema che nessuna specifica tecnica può risolvere da sola: un agente che agisce per conto di un brand deve sapere non solo *cosa può fare*, ma *cosa dovrebbe fare* — e *cosa deve rifiutare*.

Questa distinzione non è tecnica. È valoriale.

---

## Tre ere, una disciplina

| Era | Chi naviga | Superficie di design | Rilevanza Specula |
|---|---|---|---|
| **UX** | Umano direttamente | Schermi, flussi, affordance | Il metodo crea l'identità che l'umano sperimenta |
| **UAX** | Umano + agente co-navigano | Handoff, delega, supervisione | Il BOS governa ciò che l'agente amplifica |
| **AX** | Agente autonomamente | Capacità, contratti, policy | Il BOS genera il layer valoriale entro cui gli agenti operano |

In UX e UAX, il BOS informa la coerenza del brand al livello umano. In AX diventa qualcosa di più strutturale: **la fonte dei vincoli che fanno sì che un agente si comporti come il brand che rappresenta**.

---

## Cosa serve all'AX — e dove il BOS lo fornisce

Cramer identifica cinque nuovi design asset necessari per i prodotti agent-ready. Il BOS genera già il fondamento valoriale che ciascuno di essi richiede:

### Policy
**Definizione AX**: Framework di governance che definisce cosa un agente può, deve e non deve fare. Limiti di spesa, trigger di escalation, condizioni di override, gate di approvazione.

**Dove il BOS le genera**: La matrice comportamentale (Ammesso / Sensibile / Vietato) del [Layer etico aperto](./07_open-ethical-layer.it.md) e il Brand Governance Playbook sono Policy. Il Refusal Register documenta ogni confine che il brand ha deliberatamente scelto di far rispettare. Non sono configurazioni tecniche: sono l'output di una governance deliberativa che il Circolo di Sintesi ha validato rispetto ai valori radicali del brand.

> Senza il processo valoriale del BOS, le Policy sono convenzioni contrattuali. Con esso, sono espressioni di identità.

### Skill
**Definizione AX**: Istruzioni confezionate che insegnano a un agente come usare correttamente un prodotto — guida strutturata e context-efficient caricata quando un compito specifico deve essere eseguito.

**Dove il BOS le genera**: Lo Specula Agent (Layer 07 · INTERFACE) è una skill configurata sul brand: porta il DNA del brand, conosce i suoi scenari, ha accesso alla Decision Memory e al Refusal Register, ed è sottoposto a onboarding attraverso casi decisionali reali (vedi [Onboarding dell'Agent](../workshops/onboarding-agent.it.md)). Non è un assistente generico: è un interlocutore portatore di valori.

### Contratti
**Definizione AX**: Specifiche operative oltre gli endpoint API — nomi stabili, input/output tipizzati, pre/post-condizioni, side effect espliciti, procedure di rollback, classificazione del blast radius.

**Dove il BOS li genera**: Il [specula-framework](https://github.com/oddtitoreal/specula-framework) fornisce i contratti runtime (schemi JSON, specifiche di fase, envelope degli artefatti) che rendono gli output del BOS machine-readable e agent-operabili. La matrice comportamentale si mappa direttamente su permission scope e dichiarazioni di side effect.

### Evaluation set
**Definizione AX**: Golden task, regression test, criteri di accettazione — l'equivalente agentivo dei test di usabilità.

**Dove il BOS li genera**: Il workshop di Onboarding dell'Agent usa decisioni reali passate come casi di valutazione: l'agente avrebbe segnalato coerenza o drift? Le divergenze tra le risposte dell'agente e le decisioni effettivamente prese diventano il dataset di calibrazione. Non è usability testing: è value coherence testing.

### Runbook
**Definizione AX**: Percorsi di recovery strutturati per i fallimenti — cosa è successo, perché, e cosa tentare dopo.

**Dove il BOS li genera**: Il Guardian Loop e il trigger di Re-Speculation definiscono il protocollo di recovery a livello di identità del brand: quando i segnali divergono per due cicli consecutivi, il sistema propone il rientro nel layer più vicino all'origine del problema. È un runbook per il drift identitario, non solo per il fallimento tecnico.

---

## Il layer mancante che Cramer nomina ma non costruisce

Il framework di Cramer è preciso su come appaiono tecnicamente i design asset dell'AX. Quello che non affronta è come un'organizzazione decide *cosa mettere dentro* quegli asset — in particolare le Policy.

Le Policy che emergono dalla revisione legale sono documenti di compliance. Le Policy che emergono da un processo valoriale deliberativo sono artefatti di identità. La differenza non è semantica: determina se un agente AI, operando autonomamente, si comporta in modi che il brand avrebbe effettivamente approvato — o semplicemente in modi che nessuno ha esplicitamente vietato.

**Il BOS è il processo che genera Policy autentiche.**

La deliberazione del Circolo di Sintesi, il workshop di Archeologia del Brand, il Value Stress Test e il Refusal Register producono esattamente ciò che i principi di AI ethics di Floridi richiedono: valori espliciti, verificabili e contestabili nel tempo. Non perché il BOS sia stato progettato per la governance AI, ma perché è stato progettato per rendere l'identità coerente sotto pressione — ed è esattamente questo che gli agenti autonomi richiedono ai brand che rappresentano.

---

## Implicazioni pratiche: cosa costruire

Se la tua organizzazione si sta muovendo verso l'AX — o ha già agenti che agiscono per suo conto — gli output del BOS si mappano direttamente sul layer tecnico:

| Artefatto BOS | Design asset AX | Come usarlo |
|---|---|---|
| Matrice comportamentale (Ammesso / Sensibile / Vietato) | Specifica delle Policy | Tradurre direttamente in permission scope e regole di vincolo per l'agente |
| Refusal Register | Vincoli negativi delle Policy | Ogni voce STOP diventa un divieto esplicito nel contratto operativo dell'agente |
| Decision Principles | Razionale delle Policy | Documentare *perché* esiste ogni vincolo — gli agenti che capiscono il ragionamento gestiscono meglio i casi limite |
| Configurazione dello Specula Agent | Definizione della Skill | L'architettura del prompt e la struttura della memoria dall'Onboarding diventano il pacchetto skill dell'agente |
| Brand Memory | Contesto dell'agente | DNA, scenari e storia decisionale informano le risposte dell'agente in situazioni ambigue |
| Guardian Report | Baseline di valutazione | I controlli periodici di coerenza misurano se il comportamento dell'agente riflette ancora l'identità attuale del brand |

---

## Una nota su autonomia e governance

L'era AX non elimina la necessità di governance umana — la rende più urgente. La regola fondamentale di Cramer e quella di Specula coincidono:

> **L'agente suggerisce ed esegue. L'umano decide cosa è ammissibile.**

La Re-Speculation, il trigger che riavvia un ciclo BOS quando la realtà diverge dai futuri immaginati, è sempre una decisione umana. Il sistema segnala la necessità. Il Circolo di Sintesi delibera. Il Brand Alchemist custodisce la memoria.

Questa non è una limitazione del sistema. È l'architettura dell'agentività responsabile.

---

*Riferimenti: Cramer, M. (2026). "Your New User Is AI Itself." · Floridi, L. et al. (2018). "An Ethical Framework for a Good AI Society." Minds and Machines, 28(4).*
