
#  Orphelinat Maison de Lumière - Site Web Officiel

Site web officiel de l'Orphelinat Maison de Lumière situé en Haïti, dédié à la transparence et à la présentation de nos actions pour les enfants orphelins.

##  À propos du projet

Ce site web a été conçu pour offrir une fenêtre transparente sur le fonctionnement quotidien de l'Orphelinat Maison de Lumière, une institution caritative située en Haïti qui accueille et prend soin d'enfants orphelins et vulnérables. Notre objectif principal est de créer une plateforme numérique accessible qui permet aux donateurs, parrains potentiels, bénévoles et au grand public de découvrir notre mission, nos activités et l'impact réel de leur soutien.

L'Orphelinat Maison de Lumière existe pour apporter espoir et stabilité aux enfants qui ont perdu leurs parents ou qui vivent dans des situations précaires. En Haïti, où des milliers d'enfants sont confrontés à la pauvreté, au manque d'éducation et à l'insécurité, notre orphelinat représente un havre de paix et d'opportunités. Nous nous engageons à fournir non seulement un toit et des repas, mais aussi une éducation de qualité, des soins médicaux, un soutien psychologique et surtout, un environnement familial chaleureux où chaque enfant peut développer son plein potentiel.

##  Mission et Vision

**Notre Mission** : Offrir aux enfants orphelins d'Haïti un foyer sécurisé, une éducation complète, des soins de santé appropriés et les outils nécessaires pour devenir des citoyens responsables et épanouis.

**Notre Vision** : Créer une société haïtienne où chaque enfant, indépendamment de sa situation familiale, a accès aux opportunités lui permettant de réaliser ses rêves et de contribuer positivement à sa communauté.

##  Fonctionnalités du site web

### 1. Présentation de l'Orphelinat
- Histoire et fondation de l'institution
- Présentation de l'équipe dirigeante et du personnel
- Visite virtuelle des installations (dortoirs, salles de classe, réfectoire, aires de jeux)
- Témoignages du personnel et des anciens résidents

### 2. Nos Enfants
- Galerie photo présentant la vie quotidienne (respect de la vie privée)
- Histoires de réussite et parcours inspirants
- Activités éducatives et récréatives
- Programmes de développement personnel

### 3. Programmes et Services
- **Éducation** : Programme scolaire, tutorat, bibliothèque
- **Santé** : Soins médicaux, suivi nutritionnel, santé mentale
- **Développement** : Activités sportives, artistiques, culturelles
- **Formation professionnelle** : Préparation à l'autonomie pour les adolescents

### 4. Transparence Financière
- Rapports annuels téléchargeables
- Utilisation détaillée des dons reçus
- Objectifs financiers et besoins actuels
- Projets en cours et futurs

### 5. Comment Aider
- **Dons ponctuels** : Système de paiement en ligne sécurisé
- **Parrainage d'enfant** : Programme de soutien mensuel personnalisé
- **Bénévolat** : Opportunités sur place et à distance
- **Partenariats** : Collaboration avec entreprises et organisations

### 6. Actualités et Événements
- Blog régulièrement mis à jour
- Événements à venir (collectes de fonds, journées portes ouvertes)
- Newsletters mensuelles
- Rapports d'impact trimestriels

### 7. Contact et Communication
- Formulaire de contact direct
- Informations pour planifier une visite
- FAQ détaillée
- Coordonnées complètes (téléphone, email, adresse physique)

## 🛠️ Technologies utilisées

Le site est développé avec des technologies modernes pour garantir performance, sécurité et accessibilité :

- **Frontend** : HTML5, CSS3, JavaScript ES6+
- **Responsive Design** : Compatible mobile, tablette et desktop
- **Optimisation SEO** : Pour une meilleure visibilité en ligne
- **Sécurité** : Protocole HTTPS, protection des données personnelles
- **Accessibilité** : Conforme aux standards WCAG pour les personnes en situation de handicap
- **Support multilingue** : Français, Créole haïtien, Anglais

##  Installation et développement local

Si vous souhaitez contribuer au développement du site ou l'exécuter localement :

### Prérequis
- Node.js (version 14.0 ou supérieure)
- npm ou yarn
- Un éditeur de code (VS Code recommandé)

### Étapes d'installation

1. **Cloner le repository**
```bash
git clone https://github.com/josue198027/orphelinat-maison-de-lumiere.git
cd orphelinat-maison-de-lumiere
```

2. **Installer les dépendances**
```bash
npm install
```

3. **Configurer les variables d'environnement**
```bash
cp .env.example .env
# Éditer .env avec vos configurations locales
```

4. **Lancer le serveur de développement**
```bash
npm run dev
```

5. **Accéder au site**
```
Ouvrir votre navigateur : http://localhost:3000
```

### Scripts disponibles
- `npm run dev` : Démarre le serveur de développement
- `npm run build` : Génère la version de production
- `npm run test` : Execute les tests unitaires
- `npm run lint` : Vérifie la qualité du code

##  Structure du projet

```
orphelinat-maison-de-lumiere/
├── public/                 # Ressources publiques
│   ├── images/            # Photos et illustrations
│   ├── documents/         # Rapports et documents téléchargeables
│   └── favicon.ico        # Icône du site
├── src/
│   ├── components/        # Composants réutilisables
│   │   ├── Header/       # En-tête de navigation
│   │   ├── Footer/       # Pied de page
│   │   ├── DonationForm/ # Formulaire de don
│   │   └── Gallery/      # Galerie photos
│   ├── pages/            # Pages principales
│   │   ├── Home/         # Page d'accueil
│   │   ├── About/        # À propos
│   │   ├── Programs/     # Nos programmes
│   │   ├── Contact/      # Contact
│   │   └── Donate/       # Faire un don
│   ├── assets/           # Ressources statiques
│   │   ├── styles/       # Fichiers CSS/SCSS
│   │   └── fonts/        # Polices personnalisées
│   ├── utils/            # Fonctions utilitaires
│   └── config/           # Fichiers de configuration
├── README.md
├── package.json
├── .env.example
└── .gitignore
```

##  Comment contribuer

Nous accueillons chaleureusement les contributions de développeurs bénévoles qui souhaitent nous aider à améliorer notre site web. Voici comment vous pouvez contribuer :

1. **Fork** le projet sur GitHub
2. **Créez une branche** pour votre fonctionnalité (`git checkout -b feature/NouvelleFonctionnalite`)
3. **Committez** vos modifications (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. **Push** vers votre branche (`git push origin feature/NouvelleFonctionnalite`)
5. **Ouvrez une Pull Request** avec une description détaillée

### Directives de contribution
- Respectez les conventions de code existantes
- Testez vos modifications avant de soumettre
- Documentez les nouvelles fonctionnalités
- Assurez-vous que votre code est accessible et responsive

##  Soutenir l'Orphelinat

Chaque contribution fait une différence dans la vie de nos enfants :

- **Don ponctuel** : Soutenez un projet spécifique (rénovation, fournitures scolaires, équipement médical)
- **Don mensuel** : Assurez la stabilité de nos opérations quotidiennes
- **Parrainage** : Créez un lien spécial avec un enfant et suivez son évolution
- **Don en nature** : Vêtements, jouets, livres, matériel scolaire
- **Compétences** : Offrez votre expertise (enseignement, santé, construction, IT)

**Impact de vos dons** :
- 50 $ : Fournitures scolaires pour un enfant pendant un an
- 100 $ : Soins médicaux pour 5 enfants
- 200 $ : Repas nutritifs pour tous les enfants pendant une semaine
- 500 $ : Formation professionnelle pour un adolescent

##  Nous contacter

**Adresse physique** :  
Orphelinat Maison de Lumière  
Mersan, Cayes, Haiti  


**Téléphone** : 50937034697  
**Email** : eglisededieu_maisondelumiere@aol.com  
**Site web** : www.eglisededieumaisondelumiere.com

**Réseaux sociaux** :  
- Facebook : [@maisondelumiere.haiti](https://facebook.com)  
- Instagram : [@maison_de_lumiere](https://instagram.com)  
- Twitter : [@MaisonLumiere](https://twitter.com)

##  Licence

Ce projet est sous licence [À définir]. Toutes les photos et contenus sont la propriété de l'Orphelinat Maison de Lumière et ne peuvent être utilisés sans autorisation.

##  Remerciements

Nous tenons à remercier :
- Tous nos donateurs et parrains fidèles
- Les bénévoles qui donnent de leur temps
- Les organisations partenaires qui nous soutiennent
- La communauté locale haïtienne
- Les développeurs qui contribuent à ce projet open-source

##  Impact et résultats

Depuis notre création :
- sensibilisation des organisations et des cadres
-  accueillis et pris en charge

---

**Ensemble, nous pouvons changer la vie de ces enfants et construire un avenir meilleur pour Haïti** 🇭🇹 

*Fait avec amour pour les enfants d'Haïti*
