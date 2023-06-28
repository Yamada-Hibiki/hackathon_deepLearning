# hackathon_deepLearning
## Le background
C'est un exercice que j'ai résolu lors de ma participation à un Hackathon qui s'est déroulé à Paris en février 2022.
## L'objectif
L'objectif de cet exercice est de prédire le chiffre (label) qui apparaît dans l'image. 
## Le caractéristique de cet exercice
Pour chaque index, on constate que la même image apparaît toujours soit à gauche, soit à droite. Nous avons remarqué que cette image est intentionnellement présente pour réduire la précision finale (final accuracy). Évidemment, cette situation était le défi posé dans le cadre de cet exercice. Nous avons supprimé cette image qui apparaît pour chaque index afin de prédire correctement le label.
## Techniques utilisées
Python, Pytorch, Réseaux de neurons, Sklearn, Matplotlib
