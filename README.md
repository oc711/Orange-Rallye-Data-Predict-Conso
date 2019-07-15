# Orange-Rallye-Data-Predict-Conso


## Analyse prédictive de consommation en ressources techniques des projets

## Description

  Le défi à relever est de coller au plus près des besoins réels en ressources d’infrastructure (serveurs, RAM, datastore, CPU) via un scoring des « captations » (i.e. besoin projet en ressources d’infra).
 
  L’idée est de bénéficier de la plus-value de l’apprentissage machine afin d’être en mesure de répondre aux besoins de nos clients (les projets) en fonction de leurs habitudes de consommation, avec le moins de retard possible, et éviter de sur-installer des ressources (et les désinstaller par conséquence), ou de sous-livrer (et de re-planifier un projet d’infra pour compléter le besoin).
 
  L’application « GRIN » de  Gestion des ressources d'infrastructure étant récente, nous avons peu d’historique. Par conséquent, nous sommes aussi bien intéressés par la facilité à enrichir votre modèle avec de nouvelles data, que par la pertinence du résultat du scoring.

## Lexique métier

Captation : représente une demande de ressources d’infrastructure (CPU, RAM, datastore, serveurs) par un projet. La clé est constituée par  le « basicat » et la « date ». 
GRIN : l’application de  Gestion des ressources d'infrastructure.
VM : serveur virtualisé.
