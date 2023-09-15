# TP OF (Organisme de Formation)

Prépavenir a besoin d'un système de gestion pour les demandes d'inscriptions aux formations du catalogue.

### Le catalogue

- Développeur Web et Web Mobile
- Concepteur Développeur d'Applications
- Webdesigner
- Référencement SEO

Le programme sera utilisé par 2 personnes (un admin et un assistant), l'objectif étant de faciliter la gestion du processus d'inscription des futurs élèves.

---

## Algorithme :

DEBUT - Un(e) candidat(e) postule

Afficher le formulaire de candidature

SI le formulaire est rempli et valide ALORS 
    le formulaire est envoyé
    un numéro de dossier est généré et attribué au candidat
    un mail de confirmation est envoyé au candidat
    un mail de notification est envoyé aux utilisateurs
    une notification est envoyée aux utilisateurs
SINON
    le formulaire n'est pas envoyé
    un message d'erreur est affiché
FIN SI

L'utilisateur peut consulter la liste des candidatures
L'utilisateur peut consulter le détail d'une candidature

TANT QUE l'utilisateur n'a pas modifié le statut de la candidature FAIRE
    un message de rappel est envoyé à l'utilisateur
FIN TANT QUE

SI l'utilisateur modifie le statut d'une candidature ALORS
    le statut est modifié
    une notification est envoyée aux utilisateurs
    la page de suivie de candidature est mise à jour
    SI le statut est "retenu" ALORS
        un mail de confirmation est envoyé au candidat
        le candidat est ajouté à la liste des retenus
    SINON
        un mail de refus est envoyé au candidat
        la candidature est archivée
    FIN SI
FIN SI

SI la candidature est validée ALORS
    le candidat est ajouté à la liste des étudiant(e)s
    un mail de confirmation est envoyé au candidat
    la candidature est archivée
SINON
    la candidature n'est pas validée
    un mail de refus est envoyé au candidat
    la candidature est archivée
FIN SI



