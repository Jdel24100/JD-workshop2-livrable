# Audit Approfondi 6 Axes & Plan d'Optimisation V3 (Normes 2026)
## Projet ATELIER NOVA — Capsule « Printemps Urbain »

> **Contexte :** Finalisation de la landing page V2 vers la version V3 de production.  
> **URL évaluée :** [https://w01-ateliernove-jd.lovable.app](https://w01-ateliernove-jd.lovable.app)  
> **Cible de référence :** Camille (29 ans, urbain·e actif·ve, adepte d'achats réfléchis, sensible à la traçabilité et aux coupes intemporelles).  
> **Positionnement :** Urban Contemporary Premium — Édition limitée (300 pièces numérotées).

---

## 1. Axe SEO / GEO 2026 (Generative Engine Optimization)

À l'horizon 2026, l'optimisation ne se limite plus aux mots-clés traditionnels de Google : elle doit permettre aux **moteurs génératifs (Google SGE, Perplexity, ChatGPT Search, Claude)** de citer la marque comme une référence crédible de mode urbaine durable.

### A. Diagnostic Actuel
* **Points forts :** Balise `<title>` et `<meta description>` bien renseignées. Un seul `<h1>` clair et des balises `<h2>` sémantiques pour chaque section.
* **Manques identifiés :**
  1. **Absence de données structurées Schema.org (JSON-LD) :** Les robots d'IA ne peuvent pas extraire automatiquement la nature des produits, l'entité de marque et les réponses de la FAQ.
  2. **Balises `alt` d'images trop courtes :** Les images manquent de description technique (matières, coupe, certification).
  3. **Absence de balise canonique et de métadonnées Open Graph complètes** pour les partages sociaux (LinkedIn, Instagram, WhatsApp).

### B. Optimisations GEO & SEO Appliquées pour la V3
1. **Intégration d'un bloc JSON-LD complet :**
   - `@type: "Brand"` (ATELIER NOVA, mode contemporaine premium durable).
   - `@type: "Product"` pour la capsule (avec tirage limité de 300 exemplaires).
   - `@type: "FAQPage"` structurant les 8 questions/réponses afin d'apparaître directement dans les réponses génératives enrichies de Google et Perplexity.
2. **Balises `alt` descriptives riches en entités nommées :**
   - `alt="Hoodie oversize lourd 450g en coton biologique certifié GOTS ATELIER NOVA - Capsule Printemps Urbain"`
   - `alt="Veste légère technique coupe-vent en nylon recyclé certifié GRS déperlant ATELIER NOVA"`
   - `alt="Tee-shirt boxy épais 240g col renforcé en jersey bio ATELIER NOVA"`
   - `alt="Pantalon cargo structuré en sergé de coton lourd coupe urbaine ATELIER NOVA"`
   - `alt="Casquette minimale 6 panels en twill de coton bio boucle brossée ATELIER NOVA"`

---

## 2. Axe Accessibilité Numérique (Normes WCAG 2.2 Niveau AA)

L'accessibilité garantit une consultation sans barrière pour tous les utilisateurs (contrastes visuels en plein soleil, navigation au clavier, synthèse vocale pour personnes malvoyantes).

### A. Diagnostic Actuel
* **Points forts :** Structure HTML sémantique (`<header>`, `<main>`, `<section>`, `<footer>`).
* **Manques identifiés :**
  1. **Contrastes des textes secondaires :** Le gris clair (`#71717A` ou `#8E8E93`) sur fond écru (`#FBFBFA`) offre un ratio de contraste d'environ 3.6:1, inférieur au minimum requis de **4.5:1** pour du texte standard.
  2. **Attributs ARIA manquants :** Le bouton burger mobile n'a pas de label textuel explicite pour lecteur d'écran (`aria-label="Menu principal"`).
  3. **Focus visible :** En navigation au clavier (touche Tab), l'indicateur de focus est peu marqué sur certains boutons.

### B. Optimisations Accessibilité Appliquées pour la V3
1. **Ajustement de la palette de contraste :** Passage des textes secondaires à un gris anthracite soutenu (`#3F3F46` / `#27272A`), portant le ratio de contraste à **7:1** (dépassement des exigences AA).
2. **Attributs ARIA exhaustifs :**
   - Bouton burger : `aria-label="Ouvrir le menu de navigation"` et `aria-expanded="false/true"`.
   - FAQ : chaque bouton d'accordéon possède `aria-expanded` relié à l'ID de son conteneur de réponse.
   - Formulaire : attribut `aria-required="true"` sur le champ email et message de validation avec `aria-live="polite"` pour avertir les lecteurs d'écran dès la soumission réussie.
3. **Focus State visible :** Ajout de styles `focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-neutral-900` sur tous les boutons et liens interactifs.

---

## 3. Axe RGPD & Protection des Données (Conformité CNIL 2026)

Le respect de la vie privée est un critère d'évaluation fondamental et une attente majeure du persona Camille (objection n°3 : crainte du spam et usage des données).

### A. Diagnostic Actuel
* **Points forts :** Le formulaire affiche un engagement anti-spam.
* **Manques identifiés :**
  1. **Case à cocher pré-cochée (Interdit par le RGPD / CNIL) :** Sur la V2, la case était cochée par défaut. Le consentement doit impérativement être un acte positif délibéré (opt-in actif).
  2. **Absence de mentions d'information obligatoires RGPD sous le formulaire :** Identité du responsable, finalité, durée de conservation et droits d'accès/rectification.
  3. **Liens légaux inactifs dans le footer :** Les liens « Mentions légales » et « Politique de confidentialité » ne menaient à aucun texte concret.

### B. Optimisations RGPD Appliquées pour la V3
1. **Consentement explicite non pré-coché :** La case à cocher démarre décochée avec un libellé clair :  
   *« J'accepte de recevoir mon invitation exclusive au lancement VIP par email. Désinscription possible en 1 clic. »*
2. **Mentions de transparence CNIL intégrées sous le bouton VIP :**
   *« Les données recueillies sont traitées par ATELIER NOVA Studio dans l'unique but de gérer votre accès prioritaire. Conservation : jusqu'à 3 mois après la fin de la campagne. Vous disposez d'un droit d'accès, de rectification et d'effacement via contact@ateliernova-studio.com. »*
3. **Modale Légale Interactive :** Les liens « Mentions légales » et « Politique de confidentialité » ouvrent désormais une modale soignée affichant les informations légales complètes (SIREN fictif d'exercice, hébergeur Lovable, politique cookies zéro traceur publicitaire).

---

## 4. Axe Éditorial & Copywriting

### A. Diagnostic Actuel
* **Points forts :** Promesse puissante (*« Le vestiaire urbain essentiel, pensé en série limitée »*), chiffres concrets (*300 pièces, 48h d'avance, confection à Porto*), réponses réécrites avec franchise en FAQ.
* **Manques identifiés :**
  1. **Incertitude temporelle :** Le visiteur ne sait pas exactement *quand* aura lieu le drop VIP (un mois ? une semaine ?).
  2. **Micro-copie produit :** Manque de repères sur les coloris disponibles pour chaque modèle.

### B. Optimisations Éditoriales Appliquées pour la V3
1. **Balise temporelle rassurante sur le formulaire :**  
   *« Drop officiel prévu mi-avril 2026. Clé d'accès VIP unique transmise 48h avant l'ouverture. »*
2. **Pastilles de teintes sur les fiches produits :** Ajout des nuances minérales coordonnées :  
   *Écru naturel • Gris béton • Vert sauge • Noir bitume*.
3. **FAQ dynamique :** Ouverture automatique de la première question (ou de la question sur les tailles) dès l'arrivée sur la section pour inviter à la lecture des réponses de fond.

---

## 5. Axe UI & Direction Artistique

### A. Diagnostic Actuel
* **Points forts :** Atmosphère minimaliste réussie, photographies de mode contemporaine valorisantes, alternance des fonds clairs et sombres.
* **Manques identifiés :**
  1. **Icône générique dans le manifeste :** Le symbole `#` sur la carte Édition Limitée évoque un réseau social plutôt qu'un atelier de couture.
  2. **Encadré de réassurance terne :** Sur mobile, le bloc de texte continu de réassurance manquait d'assise graphique.

### B. Optimisations UI Appliquées pour la V3
1. **Remplacement de l'icône `#` :** Remplacement par un insigne typographique architectural minimal `[ 300 ]` ou une icône d'étiquette d'atelier numérotée.
2. **Mise en scène du bloc réassurance :** Application d'un fond minéral subtil (`#F5F3EF`), bordure fine et badge en surtitre *« Engagements Vérifiés »* pour en faire un label de réassurance officiel.
3. **Animations subtiles :** Micro-transitions douces (200ms) au survol des cartes produits et ouverture fluide des accordéons FAQ.

---

## 6. Axe Responsive Mobile-First (2026 Mobile UX)

Plus de 75% du trafic d'une marque de mode urbaine découverte sur Instagram provient du smartphone. L'expérience mobile doit être irréprochable.

### A. Diagnostic Actuel
* **Points forts :** Grille fluide qui s'empile bien sur 1 colonne, menu burger fonctionnel.
* **Manques identifiés :**
  1. **Amorce visuelle masquée dans le Hero :** Sur smartphone, le titre, le texte et les deux boutons occupent tout le premier écran (100vh). La photo de mode n'apparaît qu'après le premier coup de scroll.
  2. **Zones tactiles des boutons du footer et de la FAQ :** Certains liens ont une hauteur de clic inférieure à 40px, augmentant les risques d'erreur tactile.
  3. **Inputs de formulaire :** Risque de zoom automatique intempestif sur iPhone si la taille de police est inférieure à 16px.

### B. Optimisations Responsive Appliquées pour la V3
1. **Amorce visuelle dès le premier écran mobile :** Réduction subtile de la taille du H1 mobile (`text-3xl` au lieu de `text-4xl`) et compacité du sous-titre pour que le haut de la photo du Hero soit visible dès le pli initial (amorce visuelle incitant naturellement au scroll).
2. **Cibles tactiles conformes (min. 48x48 px) :** Tous les boutons interactifs, liens du footer et déclencheurs d'accordéon FAQ bénéficient d'une surface de frappe minimale de 48px.
3. **Inputs de formulaire optimisés iOS :** Définition stricte de `font-size: 16px` sur les champs prénom et email pour éviter tout zoom indésirable lors du tap sur Safari iOS.

---

## Récapitulatif des 3 Corrections Concrètes (Exigence Séquence 6)

| # | Chantier | Problème V2 | Correction V3 |
| :-: | :--- | :--- | :--- |
| **1** | **Accessibilité WCAG & RGPD** | Textes secondaires peu contrastés (ratio 3.6:1), case RGPD pré-cochée. | Contrastes portés à 7:1 (`#3F3F46`), case RGPD décochée par défaut (opt-in actif conforme CNIL) + modale légale. |
| **2** | **SEO Sémantique & GEO 2026** | Absence de Schema.org, balises `alt` génériques. | Données structurées JSON-LD (`Brand`, `Product`, `FAQPage`) + 5 balises `alt` ultra-détaillées avec matières et certifications. |
| **3** | **Performance & UX Mobile** | Amorce photo absente sur 1er écran mobile, chargement synchrone des images. | Hero mobile compacté avec amorce photo visible dès 0s + zones tactiles 48px + lazy-loading natif et ratios d'aspect fixes. |
