# Règles permanentes — En Bout de Corde

Ces règles s'appliquent à toutes les sessions, sans exception. Elles ne doivent pas avoir à être rappelées.

## Mails : bannière obligatoire

- Tout mail rédigé depuis la boîte enboutdecorde34@gmail.com (brouillon, réponse, transfert ou envoi) doit **toujours** contenir la signature Gmail avec la bannière En Bout de Corde.
- Avec les outils Gmail (`create_draft`, `reply`, `send_message`, etc.), passer **systématiquement** `includeSignature: true`.
- Ne jamais taper de signature à la main (pas de « Jonathan Perherin, En Bout de Corde… ») : la signature Gmail (la bannière En Bout de Corde) la remplace.
- Après avoir créé un brouillon, vérifier que la bannière y figure bien avant de le présenter.

## Brouillons : la version modifiée par l'utilisateur fait foi

- Quand l'utilisateur a modifié lui-même un brouillon, **sa version devient la référence**. Ses modifications (ajouts, suppressions, reformulations) expriment ce qu'il veut.
- Avant toute nouvelle modification d'un brouillon, **toujours relire la version actuelle** dans Gmail (`get_draft`) et repartir de ce texte-là, jamais de l'ancien texte de Claude.
- N'appliquer que les changements demandés. Ne jamais réintroduire un passage que l'utilisateur a supprimé, ni annuler une formulation qu'il a changée.
- Si un nouveau brouillon doit être créé (par exemple pour changer les pièces jointes), y recopier exactement le texte actuel de l'utilisateur, puis supprimer l'ancien brouillon.

## Pièces jointes : noms propres, pas de « image.png »

- Ne pas recopier sous la réponse le mail d'origine quand il contient des images : ces images apparaissent comme des pièces jointes « image.png » chez le destinataire. Créer le brouillon sans `replyToMessageId` (en gardant l'objet « Re: … »).
- Donner à chaque pièce jointe un nom clair (par exemple « Devis EBDC-D-2026-031 - Bachage toiture 6 rue des Lices.pdf »), jamais un nom générique.

## Pièces administratives : un seul fichier à jour

- Le **seul** fichier de référence est le zip **« Dossier administratif En Bout de Corde.zip »**, dans le Drive, dossier « En bout de corde » du coffre Obsidian (ID Drive : `1s8qM7RAyF8bGnMvOL9PE9r104JKHz7Fm`).
- Il contient : RIB du compte professionnel, attestation RC Pro travaux en hauteur (Allianz), attestation décennale (Entoria, activité couverture), extrait RNE, avis de situation SIRENE, attestation de vigilance URSSAF, attestation de régularité fiscale.
- Pour un client, joindre ce zip plutôt que les documents un par un.
- Quand une pièce est renouvelée, reconstruire le zip avec la nouvelle version et remplacer l'ancien zip : il ne doit exister qu'un seul zip à jour.
- En tant qu'entrepreneur individuel artisan, l'entreprise n'a pas de Kbis : l'extrait RNE en tient lieu.

### Aucun doublon accepté

- Pour retrouver une pièce administrative, **quel que soit le besoin** (client, appel d'offres, leasing, banque, assurance, dossier personnel), on utilise **uniquement** ce zip.
- **Ne jamais enregistrer de copie** d'une pièce administrative ailleurs : ni dans le Drive, ni dans le coffre Obsidian, ni dans un dossier d'appel d'offres ou de client. On envoie ou on dépose le zip (ou les PDF extraits du zip, sur le moment, sans les sauvegarder).
- Si une copie isolée d'une pièce administrative est trouvée ailleurs, la signaler et proposer de la mettre à la corbeille.
- Quand une nouvelle pièce arrive (attestation renouvelée, nouvel extrait…), la mettre directement dans le zip, puis mettre l'ancienne version et le fichier reçu à la corbeille.

## Suivi des dossiers et des sessions

- Les résumés de session et le suivi des clients sont dans le coffre Obsidian, dossier Drive « En bout de corde » (notes `_RESUME session …`, `_SUIVI - tableau de bord des demandes`, `_REGISTRE - dates de validite & pieces administratives`).
- Dossier en cours : **Copro 6 rue des Lices, Marseille (M. Lionel Gottrau)**. Tout l'historique, le devis EBDC-D-2026-031 et les prochaines étapes sont dans `_RESUME session 21-11-2026 - Copro 6 rue des Lices (Gottrau).md` (ID Drive : `165tiZhN7nnii06274pfbbN9JCPUAyBG4`). Le lire avant de reprendre ce dossier.
- Le tableau `_SUIVI` est le point d'entrée : le lire en début de session et le mettre à jour à chaque avancée (ligne A-16 pour le dossier Gottrau).
- **Modifier une note existante du coffre :** le connecteur Drive ne sait pas réécrire le contenu d'un fichier existant. Méthode : télécharger la note, la modifier en gardant son format (fins de ligne comprises), la mettre à la corbeille, puis la recréer à l'identique dans le même dossier et sous le même nom.
- Les connecteurs Google Drive et Gmail sont réglés sur « Toujours autoriser » : agir sans redemander, sauf pour l'envoi d'un mail, qui reste soumis à l'accord de Jonathan.
