# Découverte — aide-mémoire non officiel

Checklist d’entretien et sélection indicative d’offres télécoms. Aucune validation de Free / iliad ou de McAfee n’est revendiquée. Les noms commerciaux identifient les produits ; aucun logo ou document interne n’est joint et aucune grille tarifaire n’est intégrée dans la version courante. Le catalogue n’est pas une garantie de disponibilité.

## Ce que fait cette version

- Fonctionnement autonome dans `index.html`, sans serveur applicatif ni dépendance distante.
- Aucun champ libre, import de fichier, nom, adresse, téléphone, identifiant client ou justificatif demandé.
- Choix et repères de l’entretien uniquement en mémoire dans l’onglet, sans envoi applicatif ni sauvegarde persistante. Pas de cookie applicatif, de suivi d’audience ou de compte ajouté.
- Remise à zéro via « Recommencer », au rechargement, en quittant la page et après 20 minutes sans interaction lorsque la page s’exécute, ou à sa reprise.
- Le panier contient des noms d’offres et des quantités, sans prix ni règles de remise. Le chiffrage et les conditions doivent être vérifiés dans les outils autorisés de l’opérateur. Ce n’est pas un devis, un contrat ou une preuve de consentement.
- Les liens externes sont fixes, sans réponse de l’entretien dans leur adresse et sans envoi de référent. Ils s’ouvrent à la demande, sans intégration dans la page.

## Limites à connaître avant un usage professionnel

L’absence de nom ne garantit pas l’anonymat : les choix peuvent concerner une personne identifiable dans le contexte d’un entretien. L’employeur et son DPO / service juridique doivent valider l’usage, les droits de publication du code, l’information des personnes et les obligations applicables. Cette notice n’est ni une autorisation de l’entreprise ni une certification RGPD.

Les droits sur un logiciel créé dans l’exercice des fonctions d’un salarié ou sur instruction de l’employeur peuvent relever de l’employeur. Rendre le code public ou ajouter un avertissement ne règle pas cette question. Aucune nouvelle licence de réutilisation n’est attribuée par cette mise à jour.

GitHub Pages reçoit des données techniques de connexion et indique journaliser les adresses IP pour la sécurité. Les sites externes appliquent leurs propres politiques. L’usage du fichier local évite le chargement depuis GitHub Pages, mais les liens externes nécessitent toujours une connexion si on les ouvre. Ni cette application ni son bouton de remise à zéro n’effacent les captures d’écran, les journaux du système ou les traces d’extensions.

Ne mettez jamais d’information client, de secret, de capture d’entretien ou de document interne dans un commit, un ticket ou une demande de modification. Le compte de publication et les métadonnées des commits sont publics. Le fichier `.gitignore` limite les ajouts locaux ordinaires ; il ne bloque ni un ajout forcé ni un téléversement depuis GitHub.

## Sécurité et maintenance

La politique de sécurité du contenu (CSP) autorise le script intégré par son empreinte SHA-256 et bloque les connexions applicatives, scripts externes, cadres, images, objets, workers et soumissions de formulaires. Les styles intégrés restent autorisés. Une CSP en balise `meta` ne remplace pas toutes les protections d’en-têtes serveur. Ce contrôle ne couvre pas les extensions, le système, l’hébergeur ni une personne autorisée à modifier le dépôt.

Toute modification du script nécessite de recalculer son empreinte CSP et de revalider le parcours avant publication. Ne réintroduisez pas de stockage, de télémétrie, de champ d’identité ou de règle commerciale interne sans examen préalable.

L’ancienne URL `Decouverte-360.html` renvoie vers `index.html`. Les anciennes versions restent consultables dans l’historique GitHub : la mise à jour ne les purge pas et ne retire pas les copies déjà téléchargées ou forkées.

## Sources et contact

- [CNIL — minimiser les données collectées](https://www.cnil.fr/fr/minimiser-les-donnees-collectees)
- [CNIL — identifier les données personnelles](https://www.cnil.fr/fr/identifier-les-donnees-personnelles)
- [GitHub Pages — données de connexion](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection)
- [Légifrance — article L113-9 du Code de la propriété intellectuelle](https://www.legifrance.gouv.fr/codes/id/LEGISCTA000006146348)
- [GitHub — retrait de données de l’historique](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository)

Publication par le compte GitHub [mickaelwentzlaff](https://github.com/mickaelwentzlaff). Pour un signalement technique, utilisez le dépôt sans joindre de données personnelles ou confidentielles. Ce document décrit la version durcie le 7 septembre 2026 ; il ne constitue pas un audit juridique complet ni des mentions légales exhaustives.
