# De Lerende Organisatiescan

Statische versie van de bestaande Netlify-scan, geschikt voor GitHub Pages.
Alle vragen, scores en vormgeving komen uit de aangeleverde deployment.
De scan rekent in de browser en vereist geen account.

## GitHub Pages

Plaats de inhoud van deze map in de hoofdmap van een GitHub-repository.
Ga naar Settings > Pages, kies Deploy from a branch en selecteer main / (root).

## Herkomst

Dit zijn gebundelde deploymentbestanden, niet de oorspronkelijke React-broncode.
De automatische TanStack-hydratie is vervangen door directe rendering van de
bestaande scancomponent. Relatieve assetpaden ondersteunen een repository-subpad.
De oorspronkelijke netlify.toml is niet nodig voor deze statische publicatie.
