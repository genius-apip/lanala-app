# LANALA-Assurances Kaloum · Application PWA

## 🚀 Mise en ligne en 4 étapes

### Étape 1 — Configurer vos clés Supabase
Ouvrez `index.html` dans Notepad (Windows) ou TextEdit (Mac).
Cherchez ces deux lignes (vers la ligne 650) :
```
const SUPABASE_URL = 'VOTRE_PROJECT_URL';
const SUPABASE_KEY = 'VOTRE_ANON_KEY';
```
Remplacez par vos vraies valeurs récupérées dans Supabase > Settings > Data API.

### Étape 2 — Créer les comptes utilisateurs dans Supabase
Dans Supabase, allez dans **Authentication > Users > Add user** et créez :
- admin@lanala-kaloum.gn · mot de passe : Lanala2026!
- assistant@lanala-kaloum.gn · mot de passe : Lanala2026!
- alpha.diallo@lanala-kaloum.gn · mot de passe : Lanala2026!

### Étape 3 — Déposer sur GitHub
1. Ouvrez votre dépôt GitHub
2. Créez un nouveau dépôt public nommé `lanala-app`
3. Uploadez tous les fichiers de ce dossier
4. Allez dans Settings > Pages > Source : main branch / root

### Étape 4 — Activer GitHub Pages
Votre app sera disponible sur :
`https://VOTRE_USERNAME.github.io/lanala-app`

## 📱 Installer sur smartphone
- **Android** : ouvrez l'URL dans Chrome → menu ⋮ → "Ajouter à l'écran d'accueil"
- **iPhone** : ouvrez dans Safari → bouton Partager → "Sur l'écran d'accueil"

## 🔑 Comptes par défaut
| Email | Rôle | Mot de passe |
|-------|------|-------------|
| admin@lanala-kaloum.gn | Admin | Lanala2026! |
| assistant@lanala-kaloum.gn | Assistant | Lanala2026! |
| alpha.diallo@lanala-kaloum.gn | Apporteur 140-001 | Lanala2026! |

## 📁 Fichiers
- `index.html` — Application complète
- `manifest.json` — Configuration PWA (installable)
- `sw.js` — Service Worker (mode hors ligne)
- `README.md` — Ce guide
