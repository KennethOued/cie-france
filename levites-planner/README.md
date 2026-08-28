# Planificateur des Lévites — CIE-France

Outil de planification des disponibilités pour les répétitions du samedi et les cultes du dimanche. Un seul lien permanent, synchronisation en temps réel.

🔗 **Lien** : https://kennethoued.github.io/cie-france/levites-planner/

---

## Utilisation (tous les membres)

**1. Ouvre le lien** (il est fixe — le même à chaque fois).

**2. Choisis ton nom** dans le menu déroulant « Je suis ».

**3. Clique sur tes cases** pour indiquer ta disponibilité :

| Icône | Signification |
|-------|---------------|
| `—`   | Pas encore répondu |
| `✓`   | Disponible |
| `~`   | Peut-être |
| `✗`   | Absent |

Chaque clic fait tourner la réponse. Les mises à jour sont sauvegardées automatiquement et visibles par tout le monde en temps réel.

---

## Utilisation (admins — Sylvain & ...)

Les admins ont accès à la section **Équipe** après authentification.

**Connexion admin**
1. Sélectionne ton nom dans le menu déroulant.
2. Un champ « Code admin » apparaît — saisis ton code PIN et appuie sur **OK**.
3. Le badge **Admin actif** confirme la connexion.

**Gérer l'équipe (section Équipe)**
- Ajouter ou retirer un membre.
- Ajouter ou retirer un accès admin (n'importe quel membre peut devenir admin).
- Changer un code PIN.

---

## Premier démarrage

Au tout premier lancement, la section **Configuration initiale** apparaît pour tout le monde :

1. Choisis ton nom dans la liste et définis un code PIN (4 chiffres recommandé).
2. Appuie sur **Confirmer** — tu es maintenant admin.
3. Connecte-toi en admin, puis ajoute le second admin via la section **Équipe**.

---

## Comment ça marche

Les disponibilités sont stockées dans une base de données Firebase (Google) et synchronisées en temps réel. Le lien est permanent — pas besoin de le re-partager à chaque mise à jour.

---

## Navigation entre les mois

Utilise les flèches **‹** et **›** en haut pour naviguer.  
Les dates passées s'affichent en grisé (lecture seule).  
La planification est limitée à 3 mois à l'avance.
