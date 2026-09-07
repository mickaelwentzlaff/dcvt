# Découverte — aide-mémoire non officiel

Checklist d’entretien et sélection indicative d’offres télécoms. Cet aide-mémoire n’est pas un outil officiel de Free / iliad ou de McAfee. Les noms commerciaux identifient les produits ; aucun logo ou document interne n’est joint et aucune grille tarifaire n’est intégrée. Le catalogue n’est pas une garantie de disponibilité.

## Fonctionnement

- Fichier autonome `index.html`, sans serveur applicatif ni dépendance distante.
- Aucun champ libre, import de fichier, nom, adresse, téléphone, identifiant client ou justificatif demandé.
- Choix et repères de l’entretien en mémoire dans l’onglet, sans envoi applicatif ni sauvegarde persistante. Pas de cookie applicatif, suivi d’audience ou compte ajouté.
- Remise à zéro via « Recommencer », au rechargement, en quittant la page et après 20 minutes sans interaction lorsque la page s’exécute, ou à sa reprise.
- Sélection de noms d’offres et de quantités, sans chiffrage ni règles de remise. Les conditions et la souscription relèvent des outils autorisés de l’opérateur. Ce n’est ni un devis, ni un contrat, ni une preuve de consentement.
- Liens externes fixes, sans réponse de l’entretien dans leur adresse et sans envoi de référent.

## Confidentialité

Lors d’un accès en ligne, l’hébergeur reçoit des données techniques de connexion, dont l’adresse IP. Le code de l’application ne lui transmet pas les choix de l’entretien. Les sites externes s’ouvrent à la demande et appliquent leurs propres règles. Le fichier peut également être utilisé localement, sans connexion tant qu’aucun lien externe n’est ouvert.

Ne partagez pas de données client, de capture d’entretien ou d’information interne. L’absence de nom ne garantit pas l’anonymat : les choix peuvent concerner une personne identifiable dans le contexte de l’entretien.

La remise à zéro n’efface pas les captures d’écran, les journaux du système ou les traces d’extensions. Les anciennes versions et copies peuvent rester accessibles : une mise à jour ne les supprime pas.

## Maintenance

La politique de sécurité du contenu (CSP) autorise le script intégré par son empreinte SHA-256 et bloque les connexions applicatives, scripts externes, cadres, images, objets, workers et soumissions de formulaires. Les styles intégrés restent autorisés. Ce contrôle ne couvre pas les extensions, le système, l’hébergeur ni une personne autorisée à modifier le code.

Toute modification du script nécessite de recalculer son empreinte CSP et de contrôler le fonctionnement avant publication. Le fichier `.gitignore` limite les ajouts locaux ordinaires ; il ne bloque pas les ajouts forcés ou les téléversements manuels.

L’ancienne URL `Decouverte-360.html` renvoie vers `index.html`.
