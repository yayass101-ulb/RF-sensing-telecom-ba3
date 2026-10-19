# RF-sensing-telecom-ba3

## Étape 1 : Pulse RF
- [ ] 1.1 Génération du pulse
  - [ ] Paramètres utilisés (fp, Tp, 1024 échantillons)
  - [ ] Figure du signal temporel
- [ ] 1.2 Spectre
  - [ ] Figure avec fft + fftshift, axe entre -24 et +24 kHz
  - [ ] Pourquoi le recentrage est nécessaire
- [ ] 1.3 Étude des paramètres
  - [ ] Variation de fp
  - [ ] Variation de Tp
- [ ] 1.4 Test audio
  - [ ] Méthode (émission périodique, enregistrement sur au moins 2 périodes)
  - [ ] Figure du signal enregistré

## Étape 2 : Réponse en fréquence du canal
- [ ] 2.1 Démonstrations
  - [ ] Une fréquence (Figure 2)
  - [ ] Plusieurs fréquences (Figure 3)
- [ ] 2.2 Choix de la grille
  - [ ] Choix de T
  - [ ] Écart entre fréquences
  - [ ] f_min et f_max
- [ ] 2.3 Module théorique de H(f)
  - [ ] Calcul analytique de |H(f)|
  - [ ] Figure en dB
- [ ] 2.4 Mesure
  - [ ] Signal multi-cosinus
  - [ ] Scénario d'enregistrement
  - [ ] |H(f)| mesuré sur la grille
  - [ ] Comparaison avec la théorie

## Étape 3 : Réponse impulsionnelle et distance
- [ ] 3.1 Paramètres
  - [ ] Choix de Q
  - [ ] Grille entre -24 et 24 kHz
- [ ] 3.2 Signal émis
  - [ ] Symétrie H(-q) = H*(q)
  - [ ] Séquence binaire ±1, comparaison avec et sans
  - [ ] Compensation côté récepteur
- [ ] 3.3 Mesure
  - [ ] Réponse en fréquence mesurée
  - [ ] Réponse impulsionnelle par IFFT
  - [ ] Identification des deux trajets
- [ ] 3.4 Distance
  - [ ] Écart de délai entre les deux pics
  - [ ] Distance d déduite et comparée à la réelle
  - [ ] Résolution et erreur
