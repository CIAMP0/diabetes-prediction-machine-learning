# contenuto repository
La repository contiene:
- un file "Diabete_Machine_Learning.ipynb" contenetne il codice python da eseguire in Google Colab.
- un file "Diabete_Machine_Learning.pdf" contenente una versione in pdf del progetto per una più facile consultazione.

# Il progetto
Il progetto prevedere l'analisi di un dataset contenente dati sanitari riguardanti divesi pazienti con diabete. 
Le features riguardano 10 diversi parametri fisiologici misurati nei pazienti e la label è un valore numerico continuo che rappresenta l'andamento della malattia un anno dopo la misurazione dei parametri.
Lo scopo del progetto è di prevedere in base ai 10 parametri analizzati l'anadamento del diabete nei pazienti dopo un anno. 
Per fare ciò è stato addestrato un modello Random Forest per la regressione, ottimizzando i parametri sullo specifico dataset.

## Risultati
Il modello ha ottenuto un punteggio R2 e MAPE sui dati di test rispettivamente di 0.47 e 0.38. 
Non è un risultato ottimale in quanto il modello riesce a spiegare solamente circa il 47% della varianza del target ed ha un errore assoluto percentuale di circa il 38%.
Questo risultato probabilmente è dovuto alla bassa dimensionalità del dataset.

# struttura progetto
- Preparazione
  - Analisi esplorativa
  - Outliers
  - Distribuzioni
  - Features Categoriche
  - Correlazioni
  - Relazioni Features/Target
  - Conclusioni analisi esplorativa
- Scelta del modello
- Set split
- Baseline model
- Processing dati
  - Outliers imputation
  - Data Augmentation
  - Gestione Multicollinearità
  - Conclusioni processing dati
- Ottimizzazione iperparametri
   - Cross Validation
   - Predizione test
- Conclusioni
