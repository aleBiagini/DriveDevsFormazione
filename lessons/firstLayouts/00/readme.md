# Lezione 1: Introduzione a Flexbox e Grid

Questa lezione introduce i fondamenti di **Flexbox** e **Grid**, due potenti strumenti CSS per creare layout moderni e responsivi.

## Obiettivo

Impareremo a utilizzare Flexbox e Grid per creare un layout di base composto da:
- Un'**intestazione** con navigazione.
- Una **sezione hero** con immagine e testo.
- Una **sezione about** con immagine e contenuto testuale.

---

## Contenuto del Progetto

La struttura del progetto è composta da due file principali:

1. **HTML (`index.html`)**
2. **CSS (`style.css`)**
---

## Struttura del Layout sviluppato

### **Header**
- Utilizza Flexbox per:
  - Allineare la **logo** e i collegamenti del **menu di navigazione**.
  - Spaziare equamente gli elementi con `justify-content: space-between`.

### **Hero**
- Utilizza CSS Grid per:
  - Sovrapporre il **testo** all'**immagine** utilizzando `grid-column` e `grid-row`.
  - Allineare il testo verticalmente con `align-self: center`.

### **About**
- Utilizza Flexbox per:
  - Disporre l'**immagine** e il **payoff** in una riga con `justify-content: center` e `gap: 2rem`.

---

## Come modificare l'esistente

Date la vostra interpretazione dei blocchi esistenti, modificandoli e realizzando dei blocchi visivamente diversi.

## Nuovi elementi da aggiungere

1. **Sezione "Team"**
   - Una griglia con 3 o 4 card per rappresentare i membri del team.
   - Ogni card può includere un'immagine, un nome e un ruolo.

2. **Sezione "Contatti"**
   - Un layout con due colonne:
     - Una colonna per una mappa o immagine.
     - Un'altra colonna con un form di contatto. (https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

3. **Footer**
   - Una riga con 3 o 4 colonne:
     - Colonna per link utili.
     - Colonna per i contatti.
     - Colonna per icone social.