# BoldText Pro

Convertisseur simple de texte en gras Unicode pour Facebook.

## Fonctionnalités
- Une seule zone de saisie
- Conversion en gras via `Ctrl+B` / `Cmd+B`
- Bouton **Tout copier**
- Design sombre avec accents vert foncé
- 100% côté client, sans tracking

## Utilisation
1. Ouvrir `index.html` dans le navigateur.
2. Saisir votre texte.
3. Sélectionner une partie et utiliser `Ctrl+B` / `Cmd+B` pour mettre en gras.
4. Cliquer sur **Tout copier**.

## Développement local
Si le copier/coller ne fonctionne pas en mode fichier, lancez un serveur local :

```bash
cd /Users/user/Downloads/projects/boldtexter
python3 -m http.server 8080 --bind 127.0.0.1
```

Puis ouvrez `http://127.0.0.1:8080`.
