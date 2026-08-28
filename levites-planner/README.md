# Planificateur des Lévites — CIE-France

Outil de planification des disponibilités pour les répétitions du samedi et les cultes du dimanche. Zéro inscription, zéro serveur — tout passe par le lien.

---

## Utilisation (tous les membres)

**1. Ouvre le lien partagé dans WhatsApp**
Le lien contient déjà les réponses de tout le monde.

**2. Choisis ton nom** dans le menu déroulant « Je suis ».

**3. Clique sur tes cases** pour indiquer ta disponibilité :

| Icône | Signification |
|-------|---------------|
| `—`   | Pas encore répondu |
| `✓`   | Disponible |
| `~`   | Peut-être |
| `✗`   | Absent |

Chaque clic fait tourner la réponse. Clique jusqu'à la bonne.

**4. Copie le lien mis à jour** (bouton en bas de page) et colle-le dans le groupe WhatsApp.
Le lien contient maintenant ta réponse ET celles des autres — c'est lui qui fait office de base de données.

> ⚠️ **Important** : il faut toujours partir du dernier lien posté dans le groupe, jamais d'un ancien lien enregistré, sinon tu écrases les réponses des autres.

---

## Utilisation (admins — Sylvain & Lionel)

Les admins ont accès à deux sections supplémentaires après authentification.

**Connexion admin**
1. Sélectionne ton nom dans le menu déroulant.
2. Un champ « Code admin » apparaît — saisis ton code PIN et appuie sur **OK**.
3. Le badge **Admin actif** confirme la connexion.

**Partager dans WhatsApp**
- **Copier le lien** : copie l'URL complète pour la coller manuellement dans le groupe.
- **Envoyer le récap WhatsApp** : ouvre WhatsApp avec un message pré-rédigé listant toutes les disponibilités du mois en cours + le lien de mise à jour. Il suffit d'appuyer sur Envoyer.

**Gérer l'équipe (section Équipe)**
- Ajouter ou retirer un membre.
- Ajouter ou retirer un accès admin (n'importe quel membre peut devenir admin).
- Changer un code PIN.

---

## Premier démarrage

Si tu ouvres l'outil pour la première fois sans URL sauvegardée :

1. La section **Configuration initiale** apparaît.
2. Choisis ton nom dans la liste et définis un code PIN (4 chiffres recommandé).
3. Appuie sur **Confirmer** — tu es maintenant admin.
4. Ajoute le second admin via la section **Accès admin** qui vient d'apparaître.
5. Copie le lien et partage-le dans le groupe — il contient la configuration.

---

## Comment ça marche

Il n'y a pas de serveur ni de base de données.  
Toutes les réponses sont encodées dans l'URL elle-même (après le `#`).  
Chaque fois que quelqu'un met à jour ses disponibilités et partage le nouveau lien, il propage les données à tout le groupe.

Le lien peut être hébergé n'importe où (Google Drive, GitHub Pages, clé USB) — il fonctionnera toujours.

---

## Navigation entre les mois

Utilise les flèches **‹** et **›** en haut pour naviguer.  
Les dates passées s'affichent en grisé (lecture seule).  
La planification est limitée à 3 mois à l'avance.

Chaque début de mois, un admin navigue vers le nouveau mois, copie le lien et le poste dans le groupe.
