Raccourcis clavier
==================

Gestion de l'édition :
----------------------

+---------------+-----------------------------------------------------------+
| Commande      | Description                                               |
+===============+===========================================================+
| :             | Ajoute une étiquette sur une ligne assembleur.            |
+---------------+-----------------------------------------------------------+
| ;             | Ajoute un commentaire à la ligne sélectionnée.            |
+---------------+-----------------------------------------------------------+
| SPACE         | Modifier le code assembleur de la ligne.                  |
+---------------+-----------------------------------------------------------+
| Alt + BkSpace | Annule la modification du code assembleur de la ligne.    |
+---------------+-----------------------------------------------------------+

Gestion des fenêtres de déboggage :
-----------------------------------

+---------------+-----------------------------------------------------------+
| Commande      | Description                                               |
+===============+===========================================================+
| Alt + B       | Bascule  sur la fenêtre des points d'arrêts.              |
+---------------+-----------------------------------------------------------+
| Alt + C       | Bascule  sur la fenêtre du CPU.                           |
+---------------+-----------------------------------------------------------+
| Alt + E       | Bascule  sur la fenêtre des bibliothèques.                |
+---------------+-----------------------------------------------------------+
| Alt + L       | Bascule  sur la fenêtre de logs d'ImmDbg.                 |
+---------------+-----------------------------------------------------------+
| Alt + M       | Bascule  sur la fenêtre de la mémoire.                    |
+---------------+-----------------------------------------------------------+

Gestion de l'exécution du programme :
-------------------------------------

+---------------+-----------------------------------------------------------+
| Commande      | Description                                               |
+===============+===========================================================+
| F7            | Exécute la prochaine instruction (entre dans une routine).|
+---------------+-----------------------------------------------------------+
| F8            | Exécute la prochaine instruction (n'entre pas dans une    |
|               | routine).                                                 |
+---------------+-----------------------------------------------------------+
| F9            | Exécute jusqu'au prochain point d'arrêt.                  |
+---------------+-----------------------------------------------------------+
| CTRL + F9     | Exécute jusqu'à la fin de la routine.                     |
+---------------+-----------------------------------------------------------+
| Alt + F9      | Exécute jusqu'à la prochaine instruction issue du code    |
|               | écrit par le programmeur.                                 |
+---------------+-----------------------------------------------------------+
| CTRL + F2     | Redémarrage le programme.                                 |
+---------------+-----------------------------------------------------------+

Procédures
==========

Capturer un clic sur un bouton :
--------------------------------

1. View
2. Windows
3. Clic droit sur le bouton concerné
4. Message breakpoint on ClassProc
5. 202 WM_LBUTTONUP
6. Break on all windows with same title
7. Pause program : On message
8. Log WinProc arguments : Never

Positionner un point d'arrêt sur une adresse en mémoire :
---------------------------------------------------------

1. View
2. Memory
3. Clic droit sur la page mémoire où se trouve l'adresse
4. Set memory breakpoint...

Références
==========

* http://www.dc214.org/notes/rev_eng/Docs/OllyDbg%20Shortcuts.pdf
* https://home.zcu.cz/~bodik/cheatsheets/reverse_engineering_cheat_sheet.pdf
