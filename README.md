# Découverte — aide-mémoire non officiel

Checklist d’entretien et sélection indicative d’offres télécoms. Cet aide-mémoire n’est pas un outil officiel de Free / iliad ou de McAfee. Les noms commerciaux identifient les produits ; aucun logo ou document interne n’est joint et aucune grille tarifaire n’est intégrée. Le catalogue n’est pas une garantie de disponibilité.

## Fonctionnement

- Fichier autonome `index.html`, sans serveur applicatif ni dépendance distante.
- Aucun champ libre, import de fichier, nom, adresse, téléphone, identifiant client ou justificatif demandé.
- Choix et repères de l’entretien en mémoire dans l’onglet, sans envoi applicatif ni sauvegarde persistante. Pas de cookie applicatif, suivi d’audience ou compte ajouté.
- Remise à zéro via « Recommencer », au rechargement, en quittant la page et après 20 minutes sans interaction lorsque la page s’exécute, ou à sa reprise.
- Sélection de noms d’offres et de quantités, sans chiffrage ni règles de remise. Les conditions et la souscription relèvent des outils autorisés de l’opérateur. Ce n’est ni un devis, ni un contrat, ni une preuve de consentement.
- Liens externes fixes, sans réponse de l’entretien dans leur adresse et sans envoi de référent.
- Profil : équipement détenu, forfaits dans le foyer et nombre chez Free. Une seule ligne et un forfait Free déjà déclaré donnent automatiquement une ligne chez Free ; aucun forfait donne automatiquement zéro. Les réponses ambiguës restent explicites, avec une option « À vérifier ».
- Un nombre de lignes Free explicitement renseigné est conservé quand le total change et reste cohérent. Une déduction valable pour une seule ligne n’est pas réutilisée pour inventer l’équipement d’un foyer plus grand. Un équipement ajouté ne force pas à redonner une information déjà connue.
- La demande principale vient en premier. Chaque rebond est amorcé par une question qui nomme son sujet : Internet à la maison ou les forfaits ailleurs, avec le nombre de lignes connu. Les boutons précisent ce qui va être comparé. Après une assistance, la permission d’élargir l’entretien nomme les sujets réellement disponibles dans le parcours.
- Un bloc par thème, des repères courts et des cibles tactiles larges. Le bouton des points restants rejoint une question manquante sans répondre à la place du conseiller. Le récapitulatif et les mots-clés supplémentaires ont été supprimés ; la dernière page sert uniquement à sélectionner les offres.
- Rebond montre connectée avec un forfait Free détenu ou envisagé, même si le téléphone est conservé. Deux repères ouverts sur la forme, le sport, le sommeil et le quotidien précèdent la proposition, sans question supplémentaire de compatibilité. Les cases indiquent les sujets abordés, sans saisie de mesure ou de détail médical.
- Un rebond forfait apparaît pour les lignes identifiées hors Free, ou pour préciser un équipement encore inconnu. Un foyer entièrement chez Free ne reçoit pas de rebond forfait supplémentaire. La sélection est plafonnée aux lignes concernées, avec une seule ligne par défaut quand le nombre reste à vérifier.
- Le changement de mobile est abordé au début de la découverte forfait. Un refus affiche une question de reprise distincte ; un second refus mène à l’assurance du mobile conservé et évite un écran téléphone redondant. Un forfait familial ne suffit pas à déduire que le client possède un forfait Free à son nom.
- L’assurance suit le mobile conservé ou changé. Les situations d’usage et les incidents précédents sont abordés pour un nouveau mobile ou une protection à étudier. Les questions sur les SMS / mails frauduleux et les fuites de données sont liées au sujet principal et ne sont pas répétées.
- Les parcours, refus, retours et changements de profil sont contrôlés par des tests de clics. La sélection retire les offres qui ne correspondent plus aux choix du parcours.
- Interface rouge, blanche et noire ; la mention non officielle est conservée.

## Confidentialité

Lors d’un accès en ligne, l’hébergeur reçoit des données techniques de connexion, dont l’adresse IP. Le code de l’application ne lui transmet pas les choix de l’entretien. Les sites externes s’ouvrent à la demande et appliquent leurs propres règles. Le fichier peut également être utilisé localement, sans connexion tant qu’aucun lien externe n’est ouvert.

Ne partagez pas de données client, de capture d’entretien ou d’information interne. L’absence de nom ne garantit pas l’anonymat : les choix peuvent concerner une personne identifiable dans le contexte de l’entretien.

La remise à zéro n’efface pas les captures d’écran, les journaux du système ou les traces d’extensions. Les anciennes versions et copies peuvent rester accessibles : une mise à jour ne les supprime pas.

## Maintenance

La politique de sécurité du contenu (CSP) autorise le script intégré par son empreinte SHA-256 et bloque les connexions applicatives, scripts externes, cadres, images, objets, workers et soumissions de formulaires. Les styles intégrés restent autorisés. Ce contrôle ne couvre pas les extensions, le système, l’hébergeur ni une personne autorisée à modifier le code.

Toute modification du script nécessite de recalculer son empreinte CSP et de contrôler le fonctionnement avant publication. Le fichier `.gitignore` limite les ajouts locaux ordinaires ; il ne bloque pas les ajouts forcés ou les téléversements manuels.

L’ancienne URL `Decouverte-360.html` renvoie vers `index.html`.
