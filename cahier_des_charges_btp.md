CAHIER DES CHARGES — SITE VITRINE BTP
========================================
Client type : Entrepreneur du BTP (maçon, entreprise de construction)
Objectif : Générer des demandes de devis via WhatsApp et téléphone
Version : 1.0 — Novembre 2026

1. PÉRIMÈTRE
------------
Site vitrine mono-page (one-page), responsive, en français.
Pas de back-office complexe. Formulaire simple + lien WhatsApp.
Hébergement : Vercel (gratuit) ou Netlify. Domaine .com ou .bj.

2. STRUCTURE DES PAGES
----------------------
2.1 Hero (plein écran)
  - Photo ou vidéo de chantier en fond
  - Nom de l'entreprise + slogan (max 8 mots)
  - Bouton CTA : "Demander un devis" → ancre formulaire
  - Numéro WhatsApp cliquable

2.2 À propos (optionnel, 3-4 lignes)
  - Qui est l'entrepreneur, depuis quand, zone d'intervention

2.3 Réalisations
  - Grille de 6 à 12 photos
  - Chaque photo : lieu, type de travaux, année
  - Lightbox au clic (zoom)
  - Filtres par catégorie : gros œuvre / finition / rénovation

2.4 Services
  - Liste courte (4-6) avec icône et 1 phrase chacune
  - Exemples : extensions, toitures, carrelage, peinture, plomberie

2.5 Témoignages (optionnel)
  - 2-3 avis clients avec prénom + ville

2.6 Formulaire devis
  - Champs : nom, téléphone (obligatoire), type de projet,
    budget approximatif (fourchette), message libre
  - Envoi par email ET notification WhatsApp
  - Message de confirmation affiché

2.7 Footer
  - Coordonnées, horaires, lien Google Maps
  - Mentions légales minimales

3. DESIGN
---------
- Palette : 2 couleurs max + neutres (blanc/gris)
- Typographie : une seule famille, lisible sur mobile
- Boutons : couleur d'accent, coins arrondis légers
- Photos : vraies photos du client (jamais de stock)
- Mobile-first : 80% du trafic sera sur smartphone

4. FONCTIONNALITÉS TECHNIQUES
-----------------------------
- Formulaire : validation côté client (JS) + envoi (Formspree,
  Web3Forms ou équivalent gratuit)
- WhatsApp : bouton flottant fixe en bas à droite
- Performance : Lighthouse > 90, images optimisées (WebP)
- SEO : balises title/description, Open Graph pour partage
- Analytics : Google Analytics 4 (version allégée)

5. CONTENU À FOURNIR PAR LE CLIENT
----------------------------------
- Logo (ou création incluse en option)
- 10-15 photos de chantiers
- Textes courts (bio, services)
- Numéro WhatsApp et email
- Zone géographique d'intervention

6. DÉLAIS ET TARIFICATION INDICATIVE
------------------------------------
- Conception + développement : 5-7 jours ouvrés
- Révisions : 2 rounds inclus
- Livraison : code source + guide d'auto-mise à jour
- Tarif indicatif : 150 000 à 300 000 FCFA selon options
  (logo, photos pro, pages supplémentaires)

7. MAINTENANCE (OPTION)
-----------------------
- Forfait mensuel : 10 000-15 000 FCFA
  - Mises à jour, sauvegardes, support WhatsApp
  - Ajout de photos/réalisations à la demande

8. CRITÈRES D'ACCEPTATION
-------------------------
- [ ] Affichage correct sur mobile (iOS/Android) et desktop
- [ ] Formulaire fonctionnel de bout en bout
- [ ] Bouton WhatsApp opérationnel
- [ ] Temps de chargement < 3 secondes sur 4G
- [ ] Client capable d'ajouter une photo seul après formation
