# RF-sensing-telecom-ba3
[ ] 1. ETAPE 1 : PULSE RF
    [ ] 1.1 Generation du pulse
        [ ] Ecrire les parametres utilises (fp, Tp, 1024 echantillons)
        [ ] Figure du signal temporel
    [ ] 1.2 Spectre
        [ ] Figure avec fft + fftshift, axe en kHz entre -24 et +24
        [ ] Expliquer pourquoi le recentrage est necessaire
    [ ] 1.3 Etude des parametres
        [ ] Faire varier fp et commenter l'effet
        [ ] Faire varier Tp et commenter l'effet
    [ ] 1.4 Test audio
        [ ] Decrire la methode (emission periodique, enregistrement sur au moins 2 periodes)
        [ ] Figure du signal enregistre

[ ] 2. ETAPE 2 : REPONSE EN FREQUENCE DU CANAL
    [ ] 2.1 Demonstrations (a rediger avec tes mots)
        [ ] Une frequence (Figure 2)
        [ ] Plusieurs frequences (Figure 3)
        [ ] Conditions sur T, f0, f1 utilisees dans la demo
    [ ] 2.2 Choix de la grille
        [ ] Justifier T
        [ ] Justifier l'ecart entre frequences
        [ ] Justifier f_min et f_max
    [ ] 2.3 Module theorique de H(f)
        [ ] Calcul analytique de |H(f)|
        [ ] Figure en dB (choisir le rapport d'amplitude et l'ecart de delai)
    [ ] 2.4 Mesure
        [ ] Generer le signal multi-cosinus
        [ ] Decrire le scenario d'enregistrement (position, mur)
        [ ] Calculer |H(f)| mesure sur la grille
        [ ] Comparer avec la theorie et commenter

[ ] 3. ETAPE 3 : REPONSE IMPULSIONNELLE ET DISTANCE
    [ ] 3.1 Parametres
        [ ] Choix de Q et justification (puissance de 2, ambiguites)
        [ ] Definition de la grille entre -24 et 24 kHz
    [ ] 3.2 Signal emis
        [ ] Utiliser la symetrie H(-q) = H*(q)
        [ ] Sequence binaire +/-1 : comparer le signal avec et sans
        [ ] Expliquer la compensation cote recepteur
    [ ] 3.3 Mesure
        [ ] Reponse en frequence mesuree
        [ ] Reponse impulsionnelle par IFFT
        [ ] Identifier les deux trajets
    [ ] 3.4 Distance
        [ ] Mesurer l'ecart de delai entre les deux pics
        [ ] En deduire d et comparer a la distance reelle
        [ ] Discuter la resolution et l'erreur
