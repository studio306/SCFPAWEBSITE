# SCFPA JamFam Hub setup

This website is connected to the SCFPA Hub editor using Website Connection ID `aa6c860a-b745-41f0-84cb-062804ff09a7`.

Create these editable fields in the Hub:

## Upcoming events and calendar

- Page key: `events`
- Field key: `items`
- Client-facing label: `Événements à venir et calendrier`
- Field type: `Repeating list`
- List type: `Shows`
- Instructions: `Ajoutez ou modifiez les événements. Chaque date met automatiquement à jour les cartes Événements à venir et le calendrier du site.`

## Infolettre issue date

- Page key: `newsletter`
- Field key: `issue_date`
- Client-facing label: `Date de l'infolettre`
- Field type: `Text`
- Instructions: `Exemple : Mai 2026`

## Infolettre title

- Page key: `newsletter`
- Field key: `issue_title`
- Client-facing label: `Titre de l'infolettre`
- Field type: `Text`
- Instructions: `Exemple : Le Ruisselet — Mai 2026`

## Infolettre PDF

- Page key: `newsletter`
- Field key: `pdf_url`
- Client-facing label: `Lien PDF de l'infolettre`
- Field type: `URL`
- Instructions: `Collez le lien public HTTPS du nouveau PDF. Les boutons Lire et Télécharger seront mis à jour ensemble.`

The current local PDF stays visible as fallback until a new PDF URL is published.
