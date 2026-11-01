# Lab n8n — Tutoriels Markdown et vidéos commentées

Six étapes pour construire un diagnostic Nginx avec n8n, Ollama et deux outils appelant des sous-workflows.

Les tutoriels reprennent le contenu des six PDF illustrés. L’étape 2 utilise la dernière version corrigée, incluant `systemctl stop nginx` avant le test de panne.

## Utilisation

1. Décompressez **tout le ZIP**.
2. Ouvrez `README.md` dans votre lecteur Markdown.
3. Conservez les dossiers `images` et `videos` à côté des fichiers `.md` : les liens sont relatifs.
4. Cliquez sur le lien vidéo dans chaque étape. Si votre lecteur autorise la balise HTML `video`, la vidéo peut aussi être lue dans la page. Sinon, ouvrez le fichier MP4 avec votre lecteur vidéo.

[Consulter le tutoriel intégral](Tutoriel-complet.md)

## Parcours

| Étape | Markdown illustré | Vidéo commentée |
|---|---|---|
| 1. Créer le premier test HTTP | [Tutoriel](Etape-01-tutoriel.md) | [Vidéo](videos/Etape-01-video-commentee.mp4) |
| 2. Configurer IF et tester l’arrêt de Nginx | [Tutoriel](Etape-02-tutoriel.md) | [Vidéo](videos/Etape-02-video-commentee.mp4) |
| 3. Connecter l’agent IA à Ollama | [Tutoriel](Etape-03-tutoriel.md) | [Vidéo](videos/Etape-03-video-commentee.mp4) |
| 4. Créer et raccorder l’outil ping | [Tutoriel](Etape-04-tutoriel.md) | [Vidéo](videos/Etape-04-video-commentee.mp4) |
| 5. Contrôler le service Nginx par SSH | [Tutoriel](Etape-05-tutoriel.md) | [Vidéo](videos/Etape-05-video-commentee.mp4) |
| 6. Raccorder le second outil et préparer le prompt | [Tutoriel](Etape-06-tutoriel.md) | [Vidéo](videos/Etape-06-video-commentee.mp4) |

## Points de repère

- Les adresses IP visibles correspondent au laboratoire de démonstration ; adaptez-les à votre environnement.
- Les temps indiqués sont ceux des vidéos de chaque étape. Pour les étapes issues de la démonstration complète, le repère d’origine est également conservé.
- La dernière vidéo s’arrête avant la rédaction du prompt final et le test autonome complet de l’agent.
- Pour poursuivre le diagnostic d’un service arrêté après l’étape 2, laissez Nginx arrêté jusqu’au moment prévu pour sa remise en service.
