| Domaine | Plugin / Outil | Commande / Déclencheur | Action / Effet |
| :--- | :--- | :--- | :--- |
| **Navigation** | `zoxide` | `z <nom_dossier>` | Saute vers le répertoire le plus pertinent correspondant au nom. |
| **Navigation** | `zoxide` | `zi` | Ouvre une interface interactive (fzf) pour choisir le dossier cible. |
| **Navigation** | `dirhistory` | `Alt` + `←` / `→` | Recule ou avance dans l'historique des dossiers visités. |
| **Navigation** | `dirhistory` | `Alt` + `↑` | Remonte d'un niveau (équivalent à `cd ..`). |
| **Navigation** | `fzf` | `Ctrl` + `T` | Recherche un fichier en temps réel dans l'arborescence courante. |
| **Fichiers** | `extract` | `extract <fichier>` | Décompresse automatiquement n'importe quelle archive (`.tar.gz`, `.zip`, etc.). |
| **Fichiers** | `copypath` | `copypath` | Copie le chemin absolu du dossier courant dans le presse-papiers. |
| **Fichiers** | `copyfile` | `copyfile <fichier>` | Copie l'intégralité du contenu texte du fichier dans le presse-papiers. |
| **Système** | `sudo` | `Échap` puis `Échap` | Préfixe la ligne de commande actuelle avec `sudo`. |
| **Système** | `archlinux` | `pacupg` | Lance une mise à jour globale (`sudo pacman -Syu`). |
| **Système** | `archlinux` | `pacrmorphan` | Supprime les dépendances système inutilisées. |
| **Système** | `systemd` | `sc-start <service>` | Démarre un service (`sudo systemctl start`). |
| **Système** | `systemd` | `sc-status <service>` | Affiche l'état d'un service (`systemctl status`). |
| **Réseau** | `ssh` | `ssh <serveur>` + `Tab` | Auto-complète les noms d'hôtes configurés dans `~/.ssh/config`. |
| **Réseau** | `tailscale` | `tailscale` + `Tab` | Auto-complétion des nœuds et arguments du réseau maillé. |
| **Git** | `git` | `gst` | Affiche le statut du dépôt (`git status`). |
| **Git** | `git` | `gcam "<message>"` | Ajoute tous les fichiers et commit en une seule commande (`git commit -am`). |
| **Git** | `git` | `glol` | Affiche l'historique des commits sous forme de graphe coloré. |
| **Git** | `github` | `repo` | Ouvre le dépôt local actuel directement dans le navigateur web. |
| **Git** | `gitignore` | `gi <lang>` | Génère les règles d'exclusion (ex: `gi python,rust > .gitignore`). |
| **Dev** | `python` | `py` | Exécute `python3`. |
| **Dev** | `python` | `mkenv` | Crée un environnement virtuel Python (`venv`) dans le dossier courant. |
| **Audit** | `fzf` | `Ctrl` + `R` | Recherche floue et interactive dans l'historique global des commandes. |
| **Audit** | `history` | `h` | Affiche l'historique complet. |
| **Audit** | `history` | `hsi <terme>` | Cherche un terme précis dans l'historique (`history | grep <terme>`). |
| **Audit** | `thefuck` | `fuck` | Corrige et ré-exécute instantanément la dernière commande tapée avec une erreur. |
| **Web** | `web-search` | `google <requête>` | Cherche sur Google via le navigateur par défaut. |
| **Web** | `web-search` | `ddg <requête>` | Cherche sur DuckDuckGo via le navigateur par défaut. |
| **Web** | *Custom* | `anime <nom>` | Cherche la série sur Anilist via le navigateur. |
| **Web** | *Custom* | `archwiki <terme>` | Lance une recherche directe sur le wiki d'Arch Linux. |
| **Web** | *Custom* | `cachywiki` | Ouvre la page d'accueil de la documentation CachyOS. |
| **Passif** | `command-not-found`| *Automatique (Erreur)* | Intercepte les commandes inexistantes et suggère le paquet `pacman` à installer. |
| **Passif** | `dotenv` | *Automatique (Dossier)* | Charge en mémoire les variables d'un `.env` à l'entrée dans un dossier. |
| **Passif** | `colored-man-pages`| *Automatique (Man)* | Applique une coloration syntaxique lors de la lecture d'un manuel (`man`). |
| **Passif** | `timer` | *Automatique (Fin)* | Affiche le temps d'exécution exact au-dessus du prompt à la fin du processus. |
| **Passif** | `bgnotify` | *Automatique (Fond)* | Déclenche une notification système (OS) à la fin d'une tâche longue. |
| **Passif** | `rust` / `gh` | `Tab` | Injection silencieuse de l'auto-complétion experte (`cargo`, `gh pr`, etc.). |
