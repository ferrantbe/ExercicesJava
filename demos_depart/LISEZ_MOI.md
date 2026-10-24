# Le point de départ des démonstrations

Chaque dossier contient l'état de départ d'une démonstration du cours : le
code tel qu'il est au moment où la démonstration commence. Vous pouvez le
lire avant la séance, ou le copier pour suivre la démonstration en même
temps qu'elle se construit.

Ces fichiers sont rangés hors des sous-projets Maven : ils ne sont pas
compilés, et certains ne compilent volontairement pas (la démonstration du
module EXC, par exemple, part d'un programme qui plante). Pour les essayer,
copiez-les dans un package de votre choix ; IntelliJ propose alors de
corriger la ligne `package` en tête de chaque fichier.

    <module>/main/    le code de départ
    <module>/test/    les classes de test de départ, s'il y en a

L'état final de chaque démonstration vous est donné en fin de module, dans
le sous-projet demos/.
