Serverless ML Pipeline – Car Evaluation
Questo progetto implementa una pipeline automatizzata di Machine Learning basata su architettura serverless.
Il sistema utilizza il dataset Car Evaluation Dataset per classificare la qualità delle automobili a partire da diverse caratteristiche.

La pipeline automatizza le principali fasi di un workflow di Machine Learning:
-upload del dataset (trigger della pipeline)
-preprocessing dei dati
-training del modello
-servizio di inferenza tramite endpoint HTTP
Il modello viene addestrato utilizzando scikit-learn e l’applicazione è containerizzata tramite Docker.

Pipeline:
-Upload dataset – il caricamento del file avvia automaticamente la pipeline.
-Preprocessing – pulizia e trasformazione dei dati.
-Training – addestramento del modello di classificazione.
-Inference – endpoint HTTP per ottenere predizioni su nuovi dati.

Tecnologie:
-Python
-scikit-learn
-Docker
