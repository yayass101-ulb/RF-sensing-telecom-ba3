# RF-sensing-telecom-ba3

## Étape 1 : Pulse RF
- [ ] 1.1 Génération du pulse
  - [ ] Écrire les paramètres utilisés (fp, Tp, 1024 échantillons)
  - [ ] Figure du signal temporel
- [ ] 1.2 Spectre
  - [ ] Figure avec fft + fftshift, axe en kHz entre -24 et +24
  - [ ] Expliquer pourquoi le recentrage est nécessaire
- [ ] 1.3 Étude des paramètres
  - [ ] Faire varier fp et commenter l'effet
  - [ ] Faire varier Tp et commenter l'effet
- [ ] 1.4 Test audio
  - [ ] Décrire la méthode (émission périodique, enregistrement sur au moins 2 périodes)
  - [ ] Figure du signal enregistré

## Étape 2 : Réponse en fréquence du canal
- [ ] 2.1 Démonstrations (à rédiger avec tes mots)
  - [ ] Une fréquence (Figure 2)
  - [ ] Plusieurs fréquences (Figure 3)
  - [ ] Conditions sur T, f0, f1 utilisées dans la démo
- [ ] 2.2 Choix de la grille
  - [ ] Justifier T
  - [ ] Justifier l'écart entre fréquences
  - [ ] Justifier f_min et f_max
- [ ] 2.3 Module théorique de H(f)
  - [ ] Calcul analytique de |H(f)|
  - [ ] Figure en dB (choisir le rapport d'amplitude et l'écart de délai)
- [ ] 2.4 Mesure
  - [ ] Générer le signal multi-cosinus
  - [ ] Décrire le scénario d'enregistrement (position, mur)
  - [ ] Calculer |H(f)| mesuré sur la grille
  - [ ] Comparer avec la théorie et commenter

## Étape 3 : Réponse impulsionnelle et distance
- [ ] 3.1 Paramètres
  - [ ] Choix de Q et justification (puissance de 2, ambiguïtés)
  - [ ] Définition de la grille entre -24 et 24 kHz
- [ ] 3.2 Signal émis
  - [ ] Utiliser la symétrie H(-q) = H*(q)
  - [ ] Séquence binaire ±1 : comparer le signal avec et sans
  - [ ] Expliquer la compensation côté récepteur
- [ ] 3.3 Mesure
  - [ ] Réponse en fréquence mesurée
  - [ ] Réponse impulsionnelle par IFFT
  - [ ] Identifier les deux trajets
- [ ] 3.4 Distance
  - [ ] Mesurer l'écart de délai entre les deux pics
  - [ ] En déduire d et comparer à la distance réelle
  - [ ] Discuter la résolution et l'erreur
