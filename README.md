# 🛍️ PayTonKawa

**PayTonKawa** est une application mobile cross-platform développée avec Flutter qui offre une expérience de shopping moderne avec réalité augmentée et scan QR.

## 📱 Fonctionnalités

- **🔐 Authentification** : Système de connexion et inscription sécurisé
- **🏠 Page d'accueil** : Interface utilisateur moderne et intuitive
- **📱 Scan QR** : Scanner de codes QR pour identifier les produits
- **🥽 Réalité Augmentée** : Visualisation 3D des produits en réalité augmentée
- **📦 Détail produit** : Affichage détaillé des informations produits
- **🌐 API Backend** : API Node.js pour la gestion des données

## 🏗️ Architecture du Projet

```
PayTonKawa/
├── API_NODEJS/          # Backend Node.js
│   ├── index.js         # Serveur principal
│   └── unittest.js      # Tests unitaires
├── PROJECT/             # Application Flutter
│   ├── lib/
│   │   ├── Views/       # Pages de l'application
│   │   ├── models/      # Modèles de données
│   │   ├── controllers/ # Contrôleurs business
│   │   ├── services/    # Services API
│   │   └── assets/      # Ressources 3D et images
│   ├── android/         # Configuration Android
│   ├── ios/             # Configuration iOS
│   ├── web/             # Configuration Web
│   └── windows/         # Configuration Windows
```

## 🚀 Installation et Démarrage

### Prérequis

- [Flutter](https://flutter.dev/docs/get-started/install) (version ≥ 3.0)
- [Node.js](https://nodejs.org/) (version ≥ 16.0)
- [Git](https://git-scm.com/)

### Installation

1. **Cloner le repository**
```bash
git clone https://github.com/ines-gharbi/payetonkawa.git
cd payetonkawa
```

2. **Configuration de l'API Backend**
```bash
cd API_NODEJS
npm install
npm start
```

3. **Configuration de l'application Flutter**
```bash
cd PROJECT
flutter pub get
flutter run
```

## 🛠️ Technologies Utilisées

### Frontend (Flutter)
- **Flutter** - Framework UI cross-platform
- **Dart** - Langage de programmation
- **ARCore/ARKit** - Réalité augmentée
- **QR Code Scanner** - Scanner de codes QR
- **Firebase** - Backend as a Service

### Backend (Node.js)
- **Node.js** - Runtime JavaScript
- **Express.js** - Framework web
- **RESTful API** - Architecture API

### Outils de Développement
- **VS Code** - Éditeur de code
- **Git** - Contrôle de version
- **GitHub** - Hébergement du code

## 📱 Plateformes Supportées

- ✅ **Android** (API 21+)
- ✅ **iOS** (iOS 11.0+)
- ✅ **Web** (Chrome, Firefox, Safari)
- ✅ **Windows** (Windows 10+)
- ✅ **macOS** (macOS 10.14+)
- ✅ **Linux** (Ubuntu 18.04+)

## 📸 Captures d'écran

*[À ajouter : captures d'écran de l'application]*

## 🧪 Tests

### Tests Backend
```bash
cd API_NODEJS
npm test
```

### Tests Flutter
```bash
cd PROJECT
flutter test
```

## 🔧 Configuration

### Variables d'Environnement
Créer un fichier `.env` dans le dossier `API_NODEJS` :
```env
PORT=3000
DATABASE_URL=your_database_url
API_KEY=your_api_key
```

### Configuration Firebase
1. Créer un projet Firebase
2. Télécharger le fichier de configuration
3. Placer `google-services.json` dans `android/app/`
4. Configurer `firebase_options.dart`

## 📚 Documentation API

L'API backend expose les endpoints suivants :

- `GET /api/products` - Récupérer la liste des produits
- `GET /api/products/:id` - Récupérer un produit spécifique
- `POST /api/auth/login` - Connexion utilisateur
- `POST /api/auth/register` - Inscription utilisateur

## 🤝 Contribution

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👨‍💻 Auteur

**Inès Gharbi**
- GitHub: [@ines-gharbi](https://github.com/ines-gharbi)

## 📞 Support

Pour toute question ou support, veuillez ouvrir une [issue](https://github.com/ines-gharbi/payetonkawa/issues) sur GitHub.

---

⭐ N'hésitez pas à donner une étoile au projet si il vous plaît !