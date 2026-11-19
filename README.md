# VICE CITY AFTER DARK — GTA VI

Prototype statique responsive, sans étape de build. Ouvrez `index.html` ou servez le dossier :

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

## Configuration avant publication

- **Marketplace :** les boutons d’achat des produits et des classiques ouvrent Amazon.fr. Les produits sans lien direct validé utilisent une recherche Amazon.fr générique.
- **Liens fournis récemment :** les liens `https://link.amazon/B0jcEEZxr`, `https://link.amazon/B02VVVfVB`, `https://link.amazon/B0fqYjwF9` et `https://link.amazon/B03a5uUMT` ont été suivis jusqu’à des fiches Amazon.fr correspondantes (PS5 Standard, GTA V PS5, The Trilogy PS4 et Red Dead Redemption 2 PS4). Les anciens liens courts non vérifiés de `GTA6.txt` restent désactivés.
- **Suivi / affiliation :** le tag Amazon global `amazonTag` reste vide. Les quatre liens courts fournis ci-dessus contiennent un suivi et peuvent générer une commission; les autres recherches génériques sont non affiliées. Les mentions correspondantes sont affichées dans la page.
- **Prix des neuf produits d’équipement :** les montants proviennent des captures Amazon.fr fournies et ne sont pas récupérés en direct : PS5 Standard 1 To — 649,99 €; Xbox Series S 1 To — 549,99 €; EA SPORTS FC 27 — 40,39 €; DualSense camouflage — 59,90 €; Xiaomi TV 32 pouces — 139,00 €; MSI MAG 276CFA E20 — 113,99 €; Turtle Beach Recon 50P — 14,99 €; chargeur OIVO — 15,98 €; NUBWO G06 Pro — 79,99 €. Ces prix peuvent changer : vérifier le vendeur, le total et la livraison.
- **Classiques :** GTA V PS5 — 16,06 € (prix affiché sur la fiche Amazon.fr); GTA: The Trilogy PS4 — 14,16 € (prix vu sur Amazon.fr, à confirmer selon l’offre); Red Dead Redemption 2 PS4 — 15,99 € (prix communiqué). Le stock de la Trilogie, annoncé à 13 exemplaires, peut changer. GTA IV a été retiré; The Trilogy est présenté comme une édition PS4, pas PS5. Vérifier les prix, vendeurs, frais et stocks au moment de l’achat.
- **Section 6 :** la section des guides a été retirée.
- **PS5 Pro :** retirée de la sélection, conformément à la demande.
- **Images produits :** la PS5, la Xbox et les trois jaquettes GTA V / Trilogy / Red Dead sont enregistrées dans `assets/products/`. Les autres miniatures sont des recadrages des captures fournies.
- **GTA VI :** sa carte produit dédiée reste différée en attendant le visuel demandé. Les liens de comparaison PS5/Xbox présents dans la section GTA VI ouvrent Amazon.fr.
- **Compte à rebours :** cible le 19 novembre 2026 à minuit dans le fuseau local du visiteur (repère indicatif). Après cette date, le site affiche « Le décompte est terminé. L'exploration commence. ».
- **Tester la phase après lancement :** ajoutez `?date=2026-11-20T12:00:00` à l’URL.
- **Vidéo :** la vidéo YouTube `mKuHZPw9_jY` est lue dans un lecteur chargé au clic. Le lien secondaire ouvre directement YouTube si l’intégration est bloquée.
- **Carte :** `leonida-map-preview.jpg` est une illustration générée, pas une carte officielle ou géographiquement vérifiée; un visuel de secours intégré apparaît si elle est indisponible.
- **Typographie :** titres, chiffres du compte à rebours et noms de ville utilisent Barlow Condensed; corps, menus, prix et boutons utilisent Inter. Les polices Google sont distantes; une pile système est prévue en repli.
