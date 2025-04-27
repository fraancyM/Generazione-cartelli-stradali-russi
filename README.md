# Generazione di cartelli stradali tramite cGAN e valutazione con rete neurale ResNet18
## Machine Learning for Vision and Multimedia

Questo progetto si è focalizzato sull’applicazione delle cGAN per la generazione di cartelli stradali russi, con l’obiettivo di creare un ampio dataset sintetico utile per l’addestramento di modelli di visione artificiale, come quelli impiegati nei veicoli autonomi. Il modello è stato addestrato per produrre segnali appartenenti a diverse categorie con un approccio ottimizzato grazie alla sperimentazione su diversi iperparametri, tra cui dimensione del vettore latente, batch size e learning rate. 

Le performance sono state valutate tramite metriche quali F1-score, Fréchet Inception Distance (FID) e la funzione di loss, confrontando le immagini generate con quelle reali. Inoltre, una rete neurale ResNet18 è stata implementata per classificare le immagini sintetiche, fornendo ulteriori insight sulla qualità del modello e sulle sue potenzialità.
