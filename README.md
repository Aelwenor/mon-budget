# Mon budget

Petite application de budget mensuel, pensée pour le téléphone :

- une page **Paramétrage** (revenus, dépenses fixes, variables, exceptionnelles, comptes bancaires) qui se reporte automatiquement sur les 12 mois ;
- des cases à cocher : quand une dépense est payée, le solde du bon compte baisse ;
- des **échéances** (paiements en plusieurs fois, crédits) avec remboursement anticipé ;
- des **enveloppes** pour les projets (économies, voyages, shopping…).

## Tes données restent chez toi

Tout est enregistré dans le navigateur de ton téléphone. Rien n'est envoyé nulle part, il n'y a ni compte ni serveur. Deux personnes qui utilisent la même adresse ont chacune leurs propres données.

Pour passer tes données sur un autre appareil : Paramétrage › Sauvegarde › « Copier mes données », puis colle le texte sur l'autre appareil et touche « Restaurer ces données ».

## L'avoir sur l'écran d'accueil

- **iPhone** : ouvre l'adresse dans Safari › Partager › Sur l'écran d'accueil.
- **Android** : ouvre l'adresse dans Chrome › ⋮ › Installer l'application.

Ensuite elle s'ouvre comme une vraie appli, même sans connexion.

## Mettre en ligne (GitHub Pages)

1. Dépôt public sur GitHub avec ces fichiers à la racine.
2. Settings › Pages › Source : *Deploy from a branch*, branche `main`, dossier `/ (root)`.
3. L'adresse est `https://<ton-compte>.github.io/<nom-du-depot>/`.

## Mettre à jour

Remplace les fichiers du dépôt. Pour que les téléphones prennent la nouvelle version tout de suite, change le numéro dans `sw.js` (`mon-budget-v1` → `mon-budget-v2`).
