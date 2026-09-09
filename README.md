# Découverte — aide-mémoire non officiel

Checklist d’entretien et sélection indicative d’offres télécoms. Cet aide-mémoire n’est pas un outil officiel de Free / iliad ou de McAfee. Les noms commerciaux identifient les produits ; aucun logo ou document interne n’est joint et aucune grille tarifaire n’est intégrée. Le catalogue n’est pas une garantie de disponibilité.

## Fonctionnement

- Fichier autonome `index.html`, sans serveur applicatif ni dépendance distante.
- Aucun champ libre, import de fichier, nom, adresse, téléphone, identifiant client ou justificatif demandé.
- Choix et repères de l’entretien en mémoire dans l’onglet, sans envoi applicatif ni sauvegarde persistante. Pas de cookie applicatif, suivi d’audience ou compte ajouté.
- Remise à zéro via « Recommencer », au rechargement, en quittant la page et après 20 minutes sans interaction lorsque la page s’exécute, ou à sa reprise.
- Sélection de noms d’offres et de quantités, sans chiffrage ni règles de remise. Les conditions et la souscription relèvent des outils autorisés de l’opérateur. Ce n’est ni un devis, ni un contrat, ni une preuve de consentement.
- Liens externes fixes, sans réponse de l’entretien dans leur adresse et sans envoi de référent.
- Profil simplifié : équipement déjà détenu, nombre de lignes du foyer et nombre de lignes Free. Les rebonds et la sélection finale tiennent compte de ces réponses.
- Repères courts, détails secondaires et affichage en deux colonnes sur tablette à partir de 700 pixels de largeur. Le compteur indique les repères restant à traiter, pas un score de vente.
- Rebond montre connectée avec un forfait Free détenu ou envisagé, même si le téléphone est conservé. Deux repères ouverts sur la forme, le sport, le sommeil et le quotidien précèdent la proposition, sans question supplémentaire de compatibilité. Les cases indiquent les sujets abordés, sans saisie de mesure ou de détail médical.
- Un rebond forfait n’apparaît que si des lignes du foyer sont identifiées hors Free ; sa sélection est plafonnée à ce nombre. Une demande principale de forfait reste accessible, avec une limite liée au nombre de lignes déclaré (une ligne pour une première souscription). Le profil corrigé réinitialise le parcours et sa sélection.
- Interface rouge, blanche et noire ; la mention non officielle est conservée.
- Relances facultatives après un refus. Le bilan des sujets distingue ce qui a été abordé, écarté ou déjà détenu ; il ne certifie ni un besoin ni un accord du client.

## Confidentialité

Lors d’un accès en ligne, l’hébergeur reçoit des données techniques de connexion, dont l’adresse IP. Le code de l’application ne lui transmet pas les choix de l’entretien. Les sites externes s’ouvrent à la demande et appliquent leurs propres règles. Le fichier peut également être utilisé localement, sans connexion tant qu’aucun lien externe n’est ouvert.

Ne partagez pas de données client, de capture d’entretien ou d’information interne. L’absence de nom ne garantit pas l’anonymat : les choix peuvent concerner une personne identifiable dans le contexte de l’entretien.

La remise à zéro n’efface pas les captures d’écran, les journaux du système ou les traces d’extensions. Les anciennes versions et copies peuvent rester accessibles : une mise à jour ne les supprime pas.

## Maintenance

La politique de sécurité du contenu (CSP) autorise le script intégré par son empreinte SHA-256 et bloque les connexions applicatives, scripts externes, cadres, images, objets, workers et soumissions de formulaires. Les styles intégrés restent autorisés. Ce contrôle ne couvre pas les extensions, le système, l’hébergeur ni une personne autorisée à modifier le code.

Toute modification du script nécessite de recalculer son empreinte CSP et de contrôler le fonctionnement avant publication. Le fichier `.gitignore` limite les ajouts locaux ordinaires ; il ne bloque pas les ajouts forcés ou les téléversements manuels.

L’ancienne URL `Decouverte-360.html` renvoie vers `index.html`.
