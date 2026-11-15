# Historique du wiki Matcha

Ce fichier décrit les évolutions des sauvegardes consultables du wiki de Tsumun. Les versions détaillées des fichiers restent accessibles dans l’historique Git du dépôt.

## 15 November 2026 — site audit and search fixes

- Keep typed terms, result counts and addresses in sync when clearing filters, reopening an index, switching between Books and Effects, or changing languages.
- Focus the search field when the mobile magnifier or keyboard shortcut opens it. Provide a labelled clear button inside filled fields.
- Reuse indexed text when searching the wiki. Display results immediately while preserving bilingual matching and ranking.
- Show book sources, enchantment levels and both sides of a villager offer within a phone's width.
- Keep skip navigation in the active article and protect explicit links from a pending scroll update.

## 15 November 2026 — recipe lookup from the overview and item index

- Search by item or ingredient directly from the overview. Open the Mud Kiln recipe by selecting its crafting pattern, drawn from the documented pack.
- Bring the first item results higher on phones. Filters, A–Z and display preferences are available in a single row of disclosures.
- Carry an item search into the recipe index. On a craftable item's page, find its crafting recipes before equipment details.

## 15 November 2026 — advancement maps and search controls

- Name each goal on the three branch maps and use the background tiles specified in the datapack. Keep conditions and rewards beside the map on wide screens.
- Search across branches above the map. Selecting a result opens its conditions on a phone. Direct links select the corresponding branch and goal.
- Move between goals with the arrow keys. Use one Tab stop for the map and keep keyboard focus visible.
- Use one labelled search action for the catalogue and the site search. Give scrollbars the colours of the selected appearance while respecting system contrast settings.

## 15 November 2026 — item and recipe indexes

- Place the search field beside the catalogue title on wide screens. Keep the result count next to the title as filters change.
- Group categories and refinements in a keyboard-operated disclosure. Categories wrap on small screens. Open Browse A–Z to pick a letter.
- Organise alphabetical item results by initial. The grid shows sprites, names and rarity. The list includes full descriptions. Relevance-ranked searches keep their original order.
- Keep keyboard focus on the selected letter while its count updates. Expose the result count as a status message.

## 15 November 2026 — reading layout and catalogue navigation

- Put the original Matcha logo, the documented version and the recipe, item and gameplay links at the top of the overview.
- Place guide contents beside the first chapter on wide screens. On a phone, the contents open on request above the article.
- Give item names more room in the inventory grid, with two columns on phones. Keep search above the categories and pair the field with its submit button.
- Group the advancement checklist count with its storage note. Keep the original frames, conditions and keyboard navigation.
- Preserve the continuous document, bilingual search, verified pack data and images in the standalone download.

## 15 November 2026 — continuous sections and prototype contributions

- Keep the complete normal sections and guide articles in the document, preserving their controls and native scrolling in both directions.
- Remove the boundary-triggered page replacement and return-to-top behaviour. The sidebar and address follow the visible section.
- Keep form IDs and labels distinct, catalogue filters intact and dialog links functional across sections.
- Use a stable compact phone header, with a search button, so changing sections does not shift the document.
- Preserve the active paragraph and query when switching language.
- Mark the project as a prototype on the overview and in the English README. Invite design/navigation improvements through contributors' own branches and pull requests; basic GitHub knowledge is expected.
- Verify continuous wheel, keyboard and emulated touch scrolling, including zero forced scroll writes and no content replacement at section boundaries.

## 15 November 2026 — scrolling between normal sections

- Remove the separate Read all page, its menu and home links, and the text-file exports.
- Continue to the next existing wiki section by scrolling past the current one; update the normal sidebar and address.
- Return to the previous section by scrolling upward from the start. Keep catalogue filters when revisiting a section.
- Continue between individual guide articles using the same behaviour.
- Keep search, saved recipes, detail dialogs and nested controls working normally.

## 15 November 2026 — withdrawn continuous reading experiment

- Add Read all: 31 continuous sections containing the guides, public item and recipe entries, and reference text.
- Update the active chapter, contents, document title and address while scrolling, without reloading the page or adding history entries.
- Add a section selector and previous/next controls; preserve the chapter on reload and language changes.
- Provide complete English and French UTF-8 text files, including offline downloads and both files in the site ZIP.
- Verify guide paragraphs and advancement conditions, text-download equality, mobile touch scrolling, deep links and navigation after leaving reading mode.

## 15 November 2026 — metallurgy and interactive advancements

- Add a dedicated advancement page with all 69 public entries, original Matcha icons and frame sprites, 279 exact completion criteria, rewards and related recipes.
- Keep a personal browser checklist, searchable entries, keyboard tree navigation and links between displayed steps. Check marks do not connect to the game.
- Expand metallurgy into eight bilingual chapters, five alloy families, ten processing routes and eight pickaxe comparisons, with direct recipe links.
- Explain steel's intermediate material, specialized smithing templates, repair materials, silver, raw diamonds and Pith.
- Clarify the complete Eye of Ender chain, fishing habitats, favorite-food trade quantities, Beacon Kindling cooldown, archaeology finds and starting crops.
- Correct the French Raw Diamond name and explain plain Elytra repairs.
- Keep English as the initial language, with Matcha and Light appearances only. Refresh the README and actual wiki screenshots.
- Validate 1,262 recipes and all public advancement conditions against the pinned release; 55 browser checks and five default-language checks pass. No in-game validation is claimed.

## 15 November 2026 — appearance

- Keep Matcha as the default appearance, with Light as the second choice.
- Remove the Claude appearance; older saved appearances fall back to Matcha.

## 15 novembre 2026 — index et navigation

- Recherche simplifiée : un seul champ visible par page d’index, un libellé permanent et les filtres secondaires dans « More filters ».
- Ajout du parcours A–Z, d’une vue en liste et du tri par nom pour l’index d’objets.
- Compteurs de catégories adaptés aux filtres courants, filtres actifs retirables individuellement et choix d’affichage conservé lors d’une remise à zéro.
- Liens directs vers les fiches d’objets et copie de liens publics pour les objets et recettes, y compris depuis la version hors connexion.
- Réduction des calculs répétés pendant la recherche, sans modifier les données documentaires du pack.
- README anglais avec des accès directs aux rubriques, deux aperçus réels et un téléchargement versionné dans Releases.
- Contrôles ajoutés pour les nouveaux filtres, le clavier, le mobile, les liens de partage et les paramètres invalides.

## 15 novembre 2026 — première sauvegarde GitHub

Version documentée : **Matcha Flavoured 1.12.9 / Minecraft Java 26.3**.

- Sauvegarde du wiki bilingue, de ses images et de son archive hors connexion.
- Ouverture en anglais par défaut, avec des liens d’entrée explicites en anglais et le bouton FR toujours disponible.
- Recherche commune aux objets, recettes, enchantements, guides et échanges, avec noms français/anglais, alias et résultats paginés.
- Présentation conservant les bruns du GUI Matcha, les textures d’origine et les thèmes Sombre, Clair et Claude.
- Intitulés de navigation agrandis et petits objets ajoutés aux catégories et premières étapes.
- Correction de trois images de progrès manquantes ; ajout du disque public « Elegy of The Abbey » et de son crédit DeBlezyBestie.
- Retrait de 17 offres de remplissage dont le datapack supprime la sortie ; rétablissement de 12 conditions de biome. L’index présente 268 offres publiques utiles.
- Clarifications concernant la corne et les happy ghasts, l’invocation du Wither, le Brise-bedrock, l’Estus et les soins alimentaires conditionnels.
- 1 262 recettes confrontées aux fichiers de la version documentée et 30 contrôles navigateur réussis.

Les sources séparées, outils de travail, archives complètes du pack et fichiers locaux ne font pas partie de cette sauvegarde publique. Aucune validation en jeu n’est revendiquée.
