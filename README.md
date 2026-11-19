# Cover labonneagence.com : prototype

Prototype de la nouvelle page d'accueil (cover animée, études de cas, offre, typologies, pied de page).
Site statique : un seul `index.html`, aucune étape de build. GSAP 3.15 et Lenis 1.3 sont chargés depuis jsDelivr.

## Lancer en local

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

## Déployer sur Vercel

Importer le dépôt sur vercel.com/new, framework « Other », sans commande de build ni dossier de sortie (racine).
`vercel.json` règle le cache des polices et des médias, et bloque l'indexation (`noindex`) tant que c'est un prototype.

## À savoir

- Polices sous licence (Maax, 205TF ; Raisonne) : dépôt à garder privé.
- Visuels et logos provisoires (recadrages de captures, images extraites des vidéos du prototype).
- Liens « Voir l'étude de cas », « En savoir plus », « Lire la suite » et mentions : `href="#"` en attendant les pages.
