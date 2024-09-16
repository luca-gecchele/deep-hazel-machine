# Titolo: **Progettazione di modelli di Machine Learning per riconoscimento di *cultivar* di nocciole**
## Abstract
.........................

__________________________________________________________________________
## Introduzione
Negli ultimi anni, l'Intelligenza Artificiale (AI) e il *Machine Learning* (ML) hanno rivoluzionato tutti i settori produttivi, tra cui anche l'agricoltura. I nuovi algoritmi che vengono sviluppati in questo senso offrono strumenti avanzati per migliorare l'efficienza, l'accuratezza e la qualità della produzione agricola. La crescente disponibilità di dati e l'aumento delle capacità di calcolo hanno aperto nuove possibilità per l'automazione dei processi, rendendo più accessibili tecniche sofisticate per la classificazione e il controllo della qualità dei prodotti agricoli.
Nel contesto del settore vinicolo, l'importanza della certificazione e della valutazione della qualità è stata ampiamente riconosciuta. Tradizionalmente, la qualità del vino è valutata tramite test fisico-chimici e sensoriali, eseguiti da esperti umani. Tuttavia, uno studio recente [[Bozza discorso#^1|[1]]] ha dimostrato come le tecniche di *Data Mining* possano essere utilizzate efficacemente per prevedere le preferenze del vino basandosi su dati analitici oggettivi, riducendo la soggettività delle valutazioni sensoriali e migliorando i processi di controllo della qualità.​ 
Parallelamente, l'applicazione delle tecniche di ML è stata esplorata anche nel riconoscimento e nella classificazione automatica di altri prodotti agricoli. Un esempio significativo è dato da un recente studio [[Bozza discorso#^2|[2]]] che utilizza una combinazione di *Convolutional Neural Networks* (CNN), *clustering fuzzy c-means* (FCM) e *SVM* per migliorare il riconoscimento delle immagini di mele. Questo approccio ha dimostrato di aumentare significativamente l'efficienza dei sistemi di raccolta automatizzata, migliorando la velocità, l'accuratezza e l'adattabilità del riconoscimento visivo degli oggetti. Il metodo ha ottenuto risultati superiori rispetto ai metodi esistenti, evidenziando il potenziale delle tecniche di *Deep Learning* per segmentare e riconoscere efficacemente le immagini dei frutti​.
Questi sviluppi sottolineano il potenziale trasformativo delle tecnologie basate su ML e AI nel settore agricolo, non solo per migliorare la qualità dei prodotti, ma anche per ridurre i costi e aumentare la sostenibilità delle pratiche produttive. Alla luce di tali progressi, si pone l'attenzione sul riconoscimento delle *cultivar* di nocciole (*Corylus avellana* L.), un prodotto agricolo di alto valore economico e nutrizionale. Sebbene la Turchia, l'Italia, gli Stati Uniti e la Spagna siano i principali produttori di nocciole, la classificazione delle diverse *cultivar* rimane una sfida significativa a causa delle sottili variazioni visive tra le varietà.

Il presente studio propone un approccio basato su *Machine Learning* per il riconoscimento automatico delle *cultivar* di nocciole. L'obiettivo è sviluppare un modello accurato, efficiente e scalabile che possa essere applicato nel contesto agroindustriale per migliorare la classificazione delle nocciole, ottimizzare i processi di produzione e supportare le decisioni degli esperti.
## Materiali e metodi
Lo studio utilizza un dataset di immagini di nocciole coltivate in 4 Paesi diversi (Georgia, Turchia, Italia e Spagna), contenente un totale di 25 immagini. Le immagini sono ad alta risoluzione (6048 x 4024 pixel) e mostrano le nocciole su uno sfondo azzurro per eliminare le distrazioni. In ciascuna immagine sono presenti da 1 a 6 raggruppamenti di 8 nocciole ciascuno. I raggruppamenti sono invero alberi distinti, ciascuno dotato di un suo numero identificativo, da cui sono state raccolte 8 nocciole. Queste ultime sono state poi disposte sullo sfondo in diverse posizioni: alcune si mostrano di lato, altre dal basso e altre dall'alto.
### *Performance metrics*
Le metriche di performance utilizzate per valutare i modelli di *deep learning* includono accuratezza, sensibilità, precisione e *F1-score*, fondamentali per identificare errori, bias e per ottimizzare i modelli.
## Risultati

## Conclusioni

## Bibliografia
1. Cortez, P., Teixeira, J., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Using data mining for wine quality assessment. In _Discovery Science: 12th International Conference, DS 2009, Porto, Portugal, October 3-5, 2009 12_ (pp. 66-79). Springer Berlin Heidelberg. ^1
2. Wang, X., Yin, S., Sun, K., Li, H., Liu, J., & Karim, S. (2020). GKFC-CNN: Modified Gaussian kernel fuzzy C-means and convolutional neural network for apple segmentation and recognition. _Journal of Applied Science and Engineering_, _23_(3), 555-561. ^2
- Dönmez, E., Kılıçarslan, S., & Diker, A. (2024). Classification of hazelnut varieties based on bigtransfer deep learning model. _European Food Research and Technology_, _250_(5), 1433-1442.


__________________________________________________________________________
# Da qui in giù è work in progress!

>[!warning] Cosa significa...?
>- **Machine Learning** è ...
>- **Data Mining** è ...
>- **Deep Learning** è ...
>- **CNN**
>- **FCM**
>- **SVM**
>- 

Il dataset che useremo (**DOMANDA 1: TEMPO PRESENTE O PASSATO?**, **DOMANDA 2: PRIMA PERSONA SINGOLARE O PLURALE**) per le nostre analisi è stato ottenuto usando algoritmi elaborati dal collega Leonardo Morotti (**DOMANDA 3: CITO IL LAVORO DI LEONARDO?**), applicati nel nostro caso di studio su un campione di nocciole fornitoci da Ferrero (**DOMANDA 4: CITARE FERRERO O ASSOLUTAMENTE NO?**).

Le nocciole hanno diverse origini (note all'azienda), ma per le successive lavorazioni è necessario conoscere non solo il luogo in cui le nocciole sono state raccolte, ma anche la provenienza geografica della cultivar, poiché queste differiscono nelle proprietà organolettiche (**AGGIUNGERE CITAZIONE**) e si preferisce utilizzarle per lavorazioni differenti. Inoltre, possono provocare danni o blocchi alle macchine di lavoro.

Tramite l'uso degli algoritmi citati sopra