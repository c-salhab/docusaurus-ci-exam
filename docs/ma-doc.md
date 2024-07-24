# Docusaurus CI/CD Exam

## Étapes du projet

1. Création du dépôt GitHub
   - Un nouveau dépôt public nommé `docusaurus-ci-exam` a été créé sur GitHub.

2. Installation de Docusaurus
   ```bash
   npx create-docusaurus@latest . classic
   ```

3. Configuration de l'intégration continue
   - Un fichier de workflow GitHub Actions a été créé dans `.github/workflows/ci.yml`

4. Développement avec Git Flow
   - Création de la branche de développement :
     ```bash
     git checkout -b dev
     ```
   - Création de branches de fonctionnalités : (example)
     ```bash
     git checkout -b feature/doc
     ```
   - Fusion des branches via Pull Requests sur GitHub

5. Documentation du projet
   - Les étapes du projet ont été documentées dans le dossier `docs/ma-doc`

## Commandes Git utilisées

Voici quelques-unes des commandes Git les plus utilisées dans ce projet :

```bash
git clone https://github.com/c-salhab/docusaurus-ci-exam.git
git checkout -b doc
git commit -m "message de commit"
git push origin doc
git checkout dev
git merge doc
git push origin dev
```

## Déploiement

Le site est automatiquement déployé sur GitHub Pages à chaque push sur la branche `main`.
