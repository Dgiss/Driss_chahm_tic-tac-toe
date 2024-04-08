Workflow Git
Le workflow Git choisi pour ce projet est le modèle Feature Branch Workflow. Ce workflow offre plusieurs avantages, notamment :

Avantages :
Isolation des fonctionnalités : Chaque fonctionnalité ou tâche est développée dans sa propre branche, ce qui permet une isolation claire des modifications.
Facilité de collaboration : Les membres de l'équipe peuvent travailler sur des fonctionnalités distinctes simultanément sans interférer avec le travail des autres.
Révision et test aisés : Les branches de fonctionnalités peuvent être révisées et testées indépendamment avant d'être fusionnées dans la branche principale.
Inconvénients :
Gestion des conflits de fusion : Avec plusieurs branches en développement simultané, la gestion des conflits de fusion peut devenir plus complexe.
Possibilité de divergence : Si les branches restent ouvertes pendant de longues périodes, il peut y avoir une divergence entre la branche principale et les branches de fonctionnalités.
Dans ce workflow, chaque fonctionnalité est développée dans une branche distincte à partir de la branche principale. Une fois terminée et testée, elle est fusionnée dans la branche principale via une Pull Request (PR) pour être intégrée dans le projet.