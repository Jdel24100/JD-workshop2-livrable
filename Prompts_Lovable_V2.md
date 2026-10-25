# ATELIER NOVA — Prompts d'Itération V2 pour Lovable

> **Projet Lovable en ligne :** [w01-ateliernove-jd.lovable.app](https://w01-ateliernove-jd.lovable.app)  
> **Objectif V2 :** Appliquer les améliorations de la Séquence 5 directement dans Lovable (polissage typographique mobile, bloc réassurance continu, FAQ enrichie avec les 3 réponses humaines réécrites).

---

## Option 1 : Le Prompt Master V2 (Recommandé — Tout-en-un)

> **Mode d'emploi :** Ouvre ton projet sur [Lovable](https://lovable.dev/), ouvre la boîte de chat et colle le prompt ci-dessous en un seul envoi.

```markdown
Applique les améliorations suivantes pour finaliser la version V2 de la landing page ATELIER NOVA :

1. HERO SECTION & TYPOGRAPHIE MOBILE :
- Conserve le titre H1 : « Le vestiaire urbain essentiel, pensé en série limitée. »
- Sur mobile (< 640px), ajuste la taille de police du H1 (ex: text-3xl ou 2rem) avec un line-height propre pour éviter tout chevauchement ou coupure disgracieuse de mot.
- Assure-toi que les deux boutons (« Rejoindre la liste VIP » et « Découvrir la capsule ») s'empilent proprement en pleine largeur sur mobile avec une marge tactile confortable.

2. SECTION RÉASSURANCE (NOUVEAU CONTENU CONTINU) :
Dans la section Engagements / Réassurance, ajoute au-dessus des 4 cartes un bloc mis en valeur contenant ce texte fluide en 3 phrases :
« Confectionnée à Porto dans des ateliers familiaux certifiés, chaque pièce ATELIER NOVA allie toiles biologiques GOTS et finitions techniques haut de gamme.
Pour vous permettre d'essayer en toute sérénité, les livraisons sont expédiées sous 48h et les retours sont 100% gratuits pendant 30 jours avec étiquette prépayée.
Un guide des tailles centimétrique précis accompagne chaque modèle afin de vous garantir un tombé impeccable dès la première commande. »

3. MISE À JOUR DE LA FAQ (8 QUESTIONS DONT 3 RÉPONSES RÉÉCRITES) :
Remplace l'ensemble des questions/réponses actuelles par les 8 questions suivantes dans l'accordéon :

Q1 : Quand aura lieu le lancement de la capsule Printemps Urbain ?
R1 : Le drop officiel aura lieu dans quelques semaines. Les membres de la liste VIP recevront leur lien privé d'accès 48 heures avant l'éventuelle ouverture au grand public (dans la limite des 300 stocks numérotés).

Q2 : Comment fonctionne concrètement l'accès prioritaire VIP ?
R2 : Vous recevrez un email contenant une clé d'accès exclusive. Cela vous permet de réserver votre taille avant l'épuisement des 300 exemplaires numérotés par pièce.

Q3 : Comment choisir ma taille sans pouvoir essayer les pièces ?
R3 : Prenez simplement votre taille habituelle pour obtenir la coupe contemporaine et légèrement ample pensée par notre studio. Si vous préférez un porté plus ajusté au corps, choisissez une taille en dessous. Un guide centimétrique ultra-précis (largeur d'épaules, longueur de manche, tour de poitrine) sera affiché sur chaque fiche lors de l'ouverture VIP.

Q4 : Que se passe-t-il si la coupe ou la taille ne me convient pas ?
R4 : Vous disposez de 30 jours après réception pour essayer tranquillement chez vous. Les retours et échanges de taille sont 100% offerts depuis la France métropolitaine et l'Union Européenne via une étiquette prépayée téléchargeable en un clic. Zéro formalité compliquée, remboursement intégral sous 4 jours.

Q5 : Où sont sourcées les matières et où sont confectionnées les pièces ?
R5 : 100% de la capsule est confectionnée au Portugal, au sein de deux ateliers familiaux spécialisés situés près de Porto. Les cotons lourds sont certifiés 100% biologiques (GOTS) et nos toiles techniques sont issues de nylon recyclé (GRS). Nous garantissons une traçabilité totale sans aucun intermédiaire opaque.

Q6 : Pourquoi limiter la production à seulement 300 pièces ?
R6 : C'est notre engagement anti-surproduction : nous ne fabriquons que ce qui a du sens, sans créer de stocks dormants destinés à être bradés.

Q7 : Quel est le positionnement tarifaire de la collection ?
R7 : Nos prix oscillent entre 40 € (accessoires) et 160 € (veste technique déperlante). Ce tarif juste rémunère directement les ateliers portugais et les matières éco-certifiées.

Q8 : Que faites-vous de mon adresse email ?
R8 : Aucun spam, aucune revente à des tiers. Votre email sert uniquement à vous envoyer l'invitation VIP et votre confirmation. Vous pouvez vous désinscrire en un clic.

4. FORMULAIRE VIP & CONFIRMATION :
- Vérifie que la soumission du formulaire masque le formulaire et affiche un message de confirmation bien visible avec coche verte : « Merci ! Votre accès prioritaire est validé. Vous recevrez votre invitation personnelle par email. »
```

---

## Option 2 : Prompts Ciblés par Étape (Itérations modulaires)

Si tu préfères faire valider chaque modification étape par étape dans Lovable :

### Étape A — Polissage du Hero & Rendu Mobile
```markdown
Dans la section Hero :
1. Sur mobile (< 640px), réduis légèrement la taille du titre H1 (« Le vestiaire urbain essentiel, pensé en série limitée. ») pour qu'il tienne de façon harmonieuse sur 3 lignes maximum sans forcer les retours à la ligne sur des petits mots.
2. Assure-toi que les deux boutons CTA restent bien visibles au-dessus du pli ou immédiatement accessibles au premier scroll sur écran smartphone.
```

### Étape B — Insertion de la Réassurance V2 (4-6 lignes)
```markdown
Dans la section « Engagements » :
Ajoute juste sous le titre « Achetez en toute confiance » un encadré élégant (fond écru / gris très clair, bordure discrète) contenant ce texte de réassurance :
« Confectionnée à Porto dans des ateliers familiaux certifiés, chaque pièce ATELIER NOVA allie toiles biologiques GOTS et finitions techniques haut de gamme. Pour vous permettre d'essayer en toute sérénité, les livraisons sont expédiées sous 48h et les retours sont 100% gratuits pendant 30 jours avec étiquette prépayée. Un guide des tailles centimétrique précis accompagne chaque modèle afin de vous garantir un tombé impeccable dès la première commande. »
Garde les 4 cartes en-dessous en version synthétique.
```

### Étape C — Remplacement de la FAQ par les 8 questions V2
```markdown
Remplace l'ensemble des questions de la section FAQ par ces 8 questions/réponses précises :

1. Quand aura lieu le lancement de la capsule Printemps Urbain ?
-> Le drop officiel aura lieu dans quelques semaines. Les membres de la liste VIP recevront leur lien privé d'accès 48 heures avant l'éventuelle ouverture au grand public.

2. Comment fonctionne concrètement l'accès prioritaire VIP ?
-> Vous recevrez un email contenant une clé d'accès exclusive pour réserver votre pièce avant l'épuisement des 300 stocks numérotés.

3. Comment choisir ma taille sans pouvoir essayer les pièces ?
-> Prenez simplement votre taille habituelle pour la coupe contemporaine et légèrement ample pensée par notre studio. Si vous préférez un porté plus fitté, prenez la taille inférieure. Un guide centimétrique précis sera affiché sur chaque fiche.

4. Que se passe-t-il si la coupe ou la taille ne me convient pas ?
-> Vous disposez de 30 jours pour essayer chez vous. Les retours et échanges sont 100% gratuits depuis la France et l'UE via une étiquette prépayée téléchargeable en un clic. Remboursement sous 4 jours.

5. Où sont sourcées les matières et où sont confectionnées les pièces ?
-> 100% de la capsule est confectionnée au Portugal, dans deux ateliers familiaux près de Porto. Cotons bio certifiés GOTS et toiles en nylon recyclé GRS. Traçabilité totale.

6. Pourquoi limiter la production à seulement 300 pièces ?
-> C'est notre engagement anti-surproduction : nous ne produisons que la juste quantité, sans stocks dormants destinés à être bradés.

7. Quel est le positionnement tarifaire de la collection ?
-> Entre 40 € (accessoires) et 160 € (veste technique). Un prix juste pour financer des ateliers équitables et des matières éco-certifiées.

8. Que faites-vous de mon adresse email ?
-> Zéro spam, aucune revente. Votre email sert uniquement à recevoir l'accès prioritaire VIP et vous pouvez vous désinscrire en un clic.
```
