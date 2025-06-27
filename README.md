# devforge

🚀 Willy’s DevForge - CLI de Création de Projets
Crafted by Raharinandrasana Willys Sadi Arnel
Bienvenue dans Willy’s DevForge, l'outil ultime pour forger des projets de développement modernes avec rapidité et élégance ! Que vous soyez un débutant ou un expert, cette CLI intuitive vous permet de créer des projets prêts à l’emploi pour une variété de frameworks et technologies en quelques clics, avec des options avancées comme Docker, ESLint, Prettier, et plus encore. ✨

🌟 Pourquoi choisir Willy’s DevForge ?

Polyvalence : Créez des projets pour React (Vite), Next.js, Node.js (Express), Vue.js, Python (Flask/Django), Laravel, ou même des projets HTML/CSS/JS simples.
Personnalisation : Choisissez votre gestionnaire de paquets (npm, yarn, pnpm), activez TypeScript, configurez un port personnalisé, et ajoutez des outils comme Docker ou Jest.
Interface sexy : Inspirée par LazyVim, l’interface colorée et interactive rend la création de projets amusante et fluide.
Gain de temps : Automatisez la configuration initiale, y compris Git, fichiers .env, et README personnalisé.
Fiabilité : Vérifications intégrées pour s’assurer que Node.js, npm, et Git sont prêts avant de commencer.


🛠️ Installation

Prérequis :

Node.js (v16 ou supérieur) : Télécharger ici
Git : Télécharger ici
Pour les projets Python : pip et Python 3.9+
Pour Laravel : PHP et Composer


Installer Willy’s DevForge :
npm install -g willys-devforge


Vérifiez l’installation :
willys-devforge --version

Vous devriez voir : Willy’s DevForge v1.0.0



🎉 Utilisation
Lancez la CLI et laissez-vous guider par une interface interactive :
willys-devforge

Étapes :

Choisissez un type de projet : React, Next.js, Node.js, Flask, Django, Laravel, Vue.js, ou HTML/CSS/JS.
Configurez : Donnez un nom à votre projet, choisissez un emplacement, un gestionnaire de paquets, et des options avancées (Docker, ESLint, Prettier, tests Jest, Git).
Mode : Sélectionnez "Débutant" pour une configuration simplifiée ou "Expert" pour des options avancées comme le port du serveur.
Créez : La CLI génère votre projet, configure Git, crée un fichier .env, et rédige un README personnalisé.

Pour afficher l’aide :
willys-devforge --help


🔥 Fonctionnalités

Choix multiples : Supporte une large gamme de frameworks et langages.
Configuration persistante : Sauvegardez vos préférences dans ~/.devforgerc pour des créations rapides.
Logs : Chaque projet créé est consigné dans logs/projects.log pour un suivi facile.
Nettoyage automatique : En cas d’erreur, les dossiers créés sont supprimés proprement.
Personnalisation avancée :
Initialisation de dépôts Git locaux ou clonage depuis un lien.
Ajout de Docker avec des fichiers Dockerfile adaptés à chaque type de projet.
Intégration d’outils de qualité de code (ESLint, Prettier) et de tests (Jest).




🖥️ Exemple de projet
Créez un projet React avec TypeScript, Docker, et Jest :
willys-devforge


Sélectionnez React (Vite).
Entrez un nom, par exemple mon-app.
Choisissez un emplacement (par défaut : dossier courant).
Sélectionnez npm comme gestionnaire de paquets.
Activez TypeScript.
Cochez les options avancées : Docker, ESLint, Prettier, Jest.
Sauvegardez la configuration (optionnel).

Résultat : Un projet React prêt à l’emploi avec un Dockerfile, un fichier .env, un README, et des tests configurés !

📚 Documentation

Commandes :
--help ou -h : Affiche l’aide.
--version ou -v : Affiche la version de la CLI.


Fichiers générés :
logs/projects.log : Historique des projets créés.
~/.devforgerc : Configuration sauvegardée.
Dockerfile, .env, .gitignore, .prettierrc, etc., selon les options choisies.



Pour plus de détails, explorez le code source sur GitHub (lien à venir).

👨‍💻 À propos du créateur
Willy’s DevForge est fièrement créé par Raharinandrasana Willys Sadi Arnel, un passionné de développement qui combine créativité et efficacité pour simplifier la vie des développeurs. Inspiré par des outils comme LazyVim, ce projet reflète une vision de productivité et d’élégance.

🤝 Contribuer
Vous souhaitez améliorer Willy’s DevForge ? Les contributions sont les bienvenues ! Forkez le projet, ajoutez des fonctionnalités, et soumettez une pull request.

Clonez le dépôt : git clone https://github.com/votre-repo/willys-devforge.git
Installez les dépendances : npm install
Testez vos modifications : node index.js


📜 Licence
Ce projet est sous licence MIT. Utilisez-le, modifiez-le, et partagez-le librement !

Crafted with 💜 by Raharinandrasana Willys Sadi Arnel
