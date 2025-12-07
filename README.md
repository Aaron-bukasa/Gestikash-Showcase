<div align="center">
  <img src="LIEN_IMAGE_MOCKUP_GESTIKASH" width="100%" alt="Gestikash Banner" />
</div>

<div align="center">
  <h1>💰 GestiKash - Desktop Treasury Management</h1>
  <p>
    <strong>Application de gestion de trésorerie multi-postes avec synchronisation hybride.</strong>
  </p>
  
  <p>
    <img src="https://img.shields.io/badge/Electron-Desktop-blue?style=for-the-badge&logo=electron" />
    <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
    <img src="https://img.shields.io/badge/SQLite-Local_DB-003B57?style=for-the-badge&logo=sqlite" />
    <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs" />
  </p>
</div>

---

### 🔒 Note sur le Code Source
> **Ce projet est une application commerciale propriétaire.**
> Le code source n'est pas public pour des raisons de propriété intellectuelle et de sécurité.
> Cependant, ce dépôt documente l'architecture technique et les défis résolus.

---

### ⚡ Les Défis Techniques (The Challenge)

Le client avait besoin d'une solution capable de fonctionner dans des zones à **connexion internet instable**, tout en garantissant la consolidation des données financière au siège.

**Solutions implémentées :**
* **Offline-First Architecture :** Utilisation d'une base locale SQLite chiffrée.
* **Sync Engine Custom :** Création d'un moteur de synchronisation bidirectionnel (Local <-> Cloud) qui se déclenche dès que la connexion est rétablie.
* **Performance :** Gestion de +10,000 transactions sans latence grâce à l'optimisation des requêtes SQL locales.

### 🛠 Stack Technique Détaillée

| Composant | Technologie | Rôle |
| :--- | :--- | :--- |
| **Core** | Electron.js | Wrapper natif pour Windows/Mac |
| **UI** | React + Tailwind | Interface utilisateur réactive |
| **Database** | SQLite + Prisma | Stockage local robuste |
| **Sécurité** | AES-256 | Chiffrement des données sensibles |

### 📸 Galerie

| Dashboard Principal | Gestion des Flux |
| :---: | :---: |
| <img src="LIEN_IMAGE_1" width="100%"> | <img src="LIEN_IMAGE_2" width="100%"> |

---

### 📬 Contact & Démo
Pour en savoir plus sur l'architecture de ce projet ou voir une démo :
**[Visiter mon Portfolio](https://aaron-bukasa.netlify.app)** ou me contacter sur **[LinkedIn](https://linkedin.com/in/aaron-bukasa-bb84b42a0)**.
