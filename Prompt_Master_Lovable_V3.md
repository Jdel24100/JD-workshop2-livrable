# ATELIER NOVA — Master Prompt Lovable V3 (Finalisation & Normes 2026)

> **Projet Lovable :** [https://w01-ateliernove-jd.lovable.app](https://w01-ateliernove-jd.lovable.app)  
> **Mode d'emploi :** Copie-colle l'intégralité du texte ci-dessous dans la boîte de dialogue de **Lovable** pour générer et publier la version finale V3.

---

```markdown
Applique les optimisations d'excellence suivantes pour finaliser la version V3 de la landing page ATELIER NOVA selon les normes web 2026 :

### 1. RGPD & CONFORMITÉ CNIL 2026
- Case à cocher du formulaire VIP : La case à cocher de consentement marketing ne doit PAS être pré-cochée (opt-in actif obligatoire). Elle doit démarrer décochée.
- Libellé de la case : « J'accepte de recevoir mon invitation exclusive au lancement VIP par email. Désinscription en 1 clic. »
- Micro-mentions légales sous le bouton d'inscription : Ajoute en texte discret (text-xs text-neutral-400) :
  « Données collectées par ATELIER NOVA Studio SAS dans le cadre exclusif de la liste VIP Printemps 2026. Conservation max : 3 mois. Droits d'accès et d'effacement via contact@ateliernova-studio.com. »
- Modale Mentions Légales & Confidentialité : Fais en sorte que le clic sur « Mentions légales » ou « Politique de confidentialité » dans le footer ouvre une boîte modale élégante et sobre contenant un texte légal clair (Société fictive ATELIER NOVA Studio, siège à Paris, hébergement Lovable/Cloudflare, politique stricte zéro revente de données et zéro cookie publicitaire tiers). Prévois un bouton de fermeture (croix ou « Fermer ») avec fermeture à la touche Echap.

### 2. ACCESSIBILITÉ NUMÉRIQUE (WCAG 2.2 AA)
- Contrastes : Ajuste tous les textes secondaires (surtitres de sections, sous-titres, descriptifs de produits, textes de réassurance) pour qu'ils utilisent une couleur gris soutenu (ex: text-neutral-600 ou text-zinc-700 sur fond clair, et text-neutral-300 sur fond noir) afin de garantir un ratio de contraste supérieur à 4.5:1.
- Navigation Clavier & Focus : Ajoute un anneau de focus visible et net (focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-neutral-900) sur tous les boutons, liens et champs de formulaire.
- Attributs ARIA :
  - Sur le bouton burger mobile : ajoute aria-label="Menu de navigation principal" et aria-expanded.
  - Sur le formulaire : ajoute aria-required="true" sur le champ email.
  - Sur le message de confirmation après inscription : ajoute aria-live="polite".

### 3. SEO & GEO 2026 (GENERATIVE ENGINE OPTIMIZATION & DONNÉES STRUCTURÉES)
- Titre et méta : Assure-toi que le titre de la page est « ATELIER NOVA — Capsule Printemps Urbain | Vestiaire Essentiel en Série Limitée » et la meta description : « Découvrez en avant-première la capsule Printemps Urbain d'ATELIER NOVA : vestiaire contemporain minimaliste, matières biologiques certifiées GOTS et série limitée à 300 exemplaires numérotés. Inscription VIP 48h avant tout le monde. »
- Balises ALT descriptives sur les 5 images produits :
  1. Hoodie : « Hoodie oversize lourd 450g en coton biologique certifié GOTS ATELIER NOVA »
  2. Veste : « Veste légère déperlante en nylon recyclé certifié GRS coupe-vent ATELIER NOVA »
  3. Tee-Shirt : « Tee-shirt boxy épais 240g col renforcé en jersey biologique ATELIER NOVA »
  4. Pantalon : « Pantalon cargo structuré en sergé de coton lourd coupe urbaine ATELIER NOVA »
  5. Casquette : « Casquette urbaine minimaliste 6 panels en twill de coton bio ATELIER NOVA »
- Données structurées JSON-LD (balise <script type="application/ld+json"> dans le head ou composant) :
  Ajoute un balisage Schema.org combinant Brand (ATELIER NOVA), Product (Capsule Printemps Urbain, 300 pièces numérotées) et FAQPage reprenant les questions/réponses de la page pour une indexation optimale sur Google SGE et Perplexity.

### 4. RESPONSIVE MOBILE-FIRST & EXPÉRIENCE TACTILE
- Amorce photo du Hero sur mobile : Sur écran smartphone (< 640px), affine légèrement la taille de police du H1 (ex: text-3xl sm:text-4xl) et réduis les marges verticales pour que le haut de la photographie de mode des silhouettes apparaisse dès le premier écran au-dessus du pli (amorce visuelle incitant naturellement au scroll).
- Cibles tactiles 48px : Tous les boutons cliquables (CTA Hero, boutons d'accordéon FAQ, liens du footer, burger) doivent avoir une hauteur minimale de frappe tactile de 48px pour un confort total au pouce.
- Taille des inputs : Assure-toi que les champs prénom et email ont au minimum un text-base (16px) sur mobile pour empêcher le zoom automatique indésirable sur Safari iPhone.

### 5. PEAUFINAGE UI, RÉASSURANCE & FAQ
- Dans la section Pourquoi (Manifeste) : Remplace l'icône générique « # » de la carte « Édition limitée » par un élégant insigne typographique minimaliste [ 300 ] ou une icône d'étiquette d'atelier.
- Dans la section Engagements : Le bloc de réassurance textuel continu (3 phrases) doit bénéficier d'un fond minéral raffiné (#F5F3EF / neutral-100) avec une bordure fine et un surtitre « ENGAGEMENTS VÉRIFIÉS » pour ressembler à un véritable certificat de transparence de marque.
- Dans la section Formulaire VIP : Ajoute au-dessus des champs la précision temporelle : « Drop officiel prévu mi-avril 2026. Invitation et lien privé envoyés par email 48h avant. »
- Dans la section FAQ : Fais en sorte que la première question (« Quand aura lieu le lancement de la capsule Printemps Urbain ? ») soit ouverte par défaut à l'arrivée sur la section pour inciter à la lecture des réponses.
```
