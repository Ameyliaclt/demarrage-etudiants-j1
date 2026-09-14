# Suivi J1 — Cap Web

Note ton avancée après chaque TP. Reste factuel, sans données personnelles. Ce fichier te sert pour la capsule et le bilan.

## TP00 — Diagnostic

- Hypothèse : problème de largeur 
- Action : Correction de la largeur du conteneur
- Résultat : résolution du problème de largeur 
- Point non compris : 

## TP01 — Démarrer

- Hypothèse : Si JS ne fonctionne pas il n'affiche pas "Votre point de départ est prêt"
- Action : Modification du nom du fichier js relié au HTML
- Résultat : Lorsque le JS ne fonctionne pas il n'affiche pas "Votre point de départ est prêt"
- Point non compris :

## TP02 — HTML

- Hypothèse : Si on remplace Main par div les repères d'accessibilité seront moins accessible
- Action : Garder le main
- Résultat : la page est bien structuré avec un main, un header et un footer
- Point non compris : Le point sur la Version, quel message est attendu ? 

## TP03 — Formulaire

- Hypothèse : Lorsqu'on appui sur entrée dans un champs multilignes cela fait un retour à la ligne
- Action : faire entrée
- Résultat : cela fonctionne bien comme mon hypothèse
- Point non compris : 

## TP04 — Responsive

- Hypothèse : Le mot dépasse le champs du conteneur 
- Action : appliquer un breakword sur le champs textarea
- Résultat : le mot est coupé lorsqu'il arrive dans un conteneur etroit
- Point non compris, test 360 / 1280 :

## Commandes essayées

Note chaque commande avec son dossier de lancement et son résultat exact. Exemple d'état local, depuis la racine étudiante :

```sh
# depuis RACINE_ETUDIANT
git status
git diff
```

Mes essais :
```sh
cd atelier
npm start
```

- Dossier : dossier racine
- Commande et résultat : lancement du server afin d'afficher la vue utilisateur
- Problème exact si blocage : 

Si Node ou Git bloque, note le message exact et continue en local sans attendre. Le double-clic sur `diagnostic/index.html` ne remplace pas le serveur pour les modules et l'envoi du TP03.

## Auto-revue finale

- Ce qui s'affiche bien :  le header s'affiche correctement en respectant l'ordre des titres sans saut de niveaux. Pour le reste le Main s'affiche correctement et l'envoie du formulaire fonctionne. 
- Ce qui reste fragile au clavier ou à 360 px :
- Ce que je veux revoir en capsule :

## Rappel Git prudent

Git reste optionnel le matin. Vérifie l'état local, ne valide que des fichiers nommés un par un et seulement si Git est configuré. Reste en local ou en ZIP sauf si le formateur précise le circuit avec fork personnel. Aucune invitation ni demande de fusion requise le matin.

## Liens

- [README](README.md)
- [TP00](tp/00-diagnostic.md)
- [TP05](tp/05-bilan.md)
- [Aide-mémoire](ressources/aide-memoire.md)
