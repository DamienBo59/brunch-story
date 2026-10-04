# Suivi des publications — Brunch Story

Journal des articles publies, classes par semaine. Mis a jour par `/create-article-geo` et `/create-article-seo`.

Repere indicatif : 4 articles par semaine, jamais bloquant.

## Semaine du 2026-09-06

Lancement du blog, 5 articles publies le meme jour (FR + EN). Ecart assume au repere hebdomadaire : un site neuf n'a aucune position a proteger, et il lui faut un socle par categorie pour que la home et les rubriques ne soient pas vides. **A ne pas reproduire** une fois le site lance, le rythme passe a 2 par semaine via la roadmap.

| Article FR | Categorie | Mot-cle vise |
|---|---|---|
| [Cafe brunch : quelle quantite prevoir et comment le reussir](https://www.brunch-story.fr/blog/cafe-brunch/) | Boissons du matin | `cafe brunch` |
| [C'est quoi un brunch : definition, horaires et composition](https://www.brunch-story.fr/blog/c-est-quoi-un-brunch/) | Organiser un brunch | `c'est quoi un brunch` |
| [Petit dejeuner sans gluten : quoi manger vraiment le matin](https://www.brunch-story.fr/blog/petit-dejeuner-sans-gluten/) | Petit dejeuner sain | `petit dejeuner sans gluten` |
| [Pancakes legers : les proportions et les gestes qui marchent](https://www.brunch-story.fr/blog/pancakes-legers/) | Pancakes et sucre | `pancakes legers` |
| [Oeuf poche : temps de cuisson exact et methode sans ratage](https://www.brunch-story.fr/blog/oeuf-poche-temps-de-cuisson/) | Oeufs et sale | `oeuf poche temps` |

Les 5 versions EN correspondantes sont publiees sous `/en/blog/`.

Suite : voir la semaine du 2026-09-12, la roadmap de 49 entrees a ete remplacee.

## Semaine du 2026-09-12

**Roadmap reconstruite sur le corpus de septembre.** Les 49 entrees baties sur le corpus d'aout (87 mots-cles) sont remplacees par **60 entrees** issues du corpus de septembre (1 906 mots-cles, 632 en longue traine ciblable), soit **72 006 de volume mensuel vise** contre des entrees a 200-700 auparavant. 12 entrees par rubrique, du 2026-09-12 au 2027-03-23, mardi et vendredi.

Filtres : 3 mots ou plus, volume 150 a 3 000, KGR sous 0,6 ; perimetre du blog respecte (gateaux, cookies, tartes et galette des rois ecartes, brioche et pain perdu gardes ici) ; requetes produit a SERP de marques ecartees en frontal ; garde-fou cannibalisation passe contre les 9 articles publies, les 49 anciennes entrees et les 60 nouvelles entre elles. Controles : 0 couple cannibalisant, 0 paire consecutive de meme categorie, au moins 3 categories sur toute fenetre de 5.

**5 articles publies (FR + EN), un par rubrique.** Deuxieme et dernier ecart au repere hebdomadaire, pour la meme raison qu'au lancement : chaque rubrique gagne un second article et sort de l'etat a un seul papier. Le rythme revient ensuite a 2 par semaine.

| Article FR | Categorie | Mot-cle vise | Volume |
|---|---|---|---|
| [Comment faire un smoothie : methode et proportions](https://www.brunch-story.fr/blog/comment-faire-un-smoothie/) | Boissons du matin | `comment faire un smoothie` | 2 636 |
| [Recette avocado toast : la methode et les proportions](https://www.brunch-story.fr/blog/recette-avocado-toast/) | Oeufs et sale | `recette avocado toast` | 1 455 |
| [Plateau petit dejeuner : quantites et composition](https://www.brunch-story.fr/blog/plateau-petit-dejeuner/) | Organiser un brunch | `plateau petit dejeuner` | 1 600 |
| [Petit dejeuner IG bas : les aliments et les valeurs](https://www.brunch-story.fr/blog/petit-dejeuner-ig-bas/) | Petit dejeuner sain | `petit dejeuner IG bas` | 1 900 |
| [Gaufres croustillantes et moelleuses : la methode](https://www.brunch-story.fr/blog/gaufres-croustillantes-moelleuses/) | Pancakes et sucre | `gaufres croustillantes et moelleuses` | 3 000 |

Les 5 versions EN correspondantes sont publiees sous `/en/blog/`. 72 liens internes verifies, aucun casse. Maillage croise entre les 5 articles du lot.

**Images : source changee.** `api.openverse.org` est injoignable depuis le Mac (timeout, et 403 sur `openverse.org`), donc `.claude/scripts/fetch-image.sh` echoue en code 28. Les 5 images viennent de **Wikimedia Commons**, l'une des sources federees par Openverse, via l'API `commons.wikimedia.org/w/api.php`, avec filtrage sur les licences autorisant l'usage commercial (CC0, CC BY, CC BY-SA, domaine public) et exclusion de `-nc` et `-nd`.

## Semaine du 2026-09-16

**5 articles publies (FR + EN), un par rubrique, en publication immediate.** Lot demande explicitement le 2026-09-16, produit en mode A de `/create-article-seo` (roadmap du blog, 5 entrees `todo` les plus anciennes) mais avec `publishDate` ramenee au jour meme au lieu des `scheduled_date` du 15 au 29 septembre. Les entrees passent donc directement en `status: done` dans la roadmap, leur `scheduled_date` d'origine etant conservee pour garder la trace de l'ecart.

**Troisieme ecart au repere hebdomadaire de 4 articles/semaine**, apres ceux du 2026-09-06 et du 2026-09-12 qui etaient annonces comme les deux derniers. Celui-ci est une demande directe, pas une decision de la skill. Le rythme de 2 par semaine reste l'objectif.

| Article FR | Categorie | Mot-cle vise | Volume |
|---|---|---|---|
| [Smoothie fruits rouges : les proportions](https://www.brunch-story.fr/blog/smoothie-fruits-rouges/) | Boissons du matin | `smoothie fruits rouges` | 2 769 |
| [Pain perdu sans œuf : la methode](https://www.brunch-story.fr/blog/pain-perdu-sans-oeuf/) | Oeufs et sale | `pain perdu sans oeuf` | 2 417 |
| [Petit dejeuner turc : ce qu'il y a dessus](https://www.brunch-story.fr/blog/petit-dejeuner-turc/) | Organiser un brunch | `petit dejeuner turc` | 1 600 |
| [Bienfaits des graines de chia : les faits](https://www.brunch-story.fr/blog/bienfaits-graines-de-chia/) | Petit dejeuner sain | `bienfaits des graines de chia` | 1 900 |
| [Recette brioche a l'ancienne : la methode](https://www.brunch-story.fr/blog/recette-brioche-a-l-ancienne/) | Pancakes et sucre | `recette brioche a l'ancienne` | 2 700 |

Les 5 versions EN sont publiees sous `/en/blog/` : `berry-smoothie`, `eggless-french-toast`, `turkish-breakfast`, `chia-seed-benefits`, `old-fashioned-brioche`. Maillage croise entre les 5 articles du lot, 4 a 5 liens internes contextuels par article, tous verifies sur le site genere.

**Analyse SERP en mode degrade assume** : le MCP `serpapi` n'est pas disponible, donc l'analyse s'est faite par recherche web (titres et snippets), sans fetch des concurrents. Aucun geant ne tient le top 3 sur les 5 requetes.

**Images : 2 rejets sur 5 au controle visuel**, ce qui confirme la mesure du 2026-09-12. `berry smoothie` a remonte un gobelet McDonald's McCafe, et `brioche bread` un rayon de supermarche avec des sachets Reflets de France : deux visuels de marque qui contredisent en plus l'angle « ce qui se refait mieux chez soi ». Relancer le script avec une autre query ne suffit pas toujours : le registre `hero-sources.json` n'exclut que les photos utilisees par un AUTRE slug, donc un second passage sur le meme slug peut retomber sur la photo rejetee (c'est arrive pour la brioche). La parade est de chercher directement dans l'API Commons et de deposer l'image a la main, puis de corriger l'entree du registre.

**Piege de fuseau horaire sur `publishDate`** : une date seule (`"2026-09-16"`) est lue par Hugo comme minuit **UTC**. Ecrite depuis Paris entre minuit et 2 h du matin, elle est donc dans le futur et `buildFuture: false` masque l'article, sans aucune erreur au build. Le correctif applique est une date horodatee avec fuseau explicite (`"2026-09-15T23:00:00+02:00"`), `date` et `lastmod` restant au 2026-09-16 puisque c'est `.Date` que le theme affiche.

**A traiter, defaut anterieur au lot** : sur toutes les pages EN, les liens de tags pointent vers `/tags/<slug-en>/` au lieu de `/en/tags/<slug-en>/`, soit **63 liens internes en 404**. Les pages de destination existent bien sous `/en/tags/`. La cause est une URL ecrite en dur dans `themes/brunch-story/layouts/_default/single.html` ligne 92 (`{{ "/tags/" | relURL }}`), qui ignore la langue courante. Le defaut touchait deja les 10 articles EN publies avant ce lot, il n'a pas ete corrige ici pour ne pas melanger un changement de theme a une publication.

## Semaine du 2026-09-20

**5 articles produits (FR + EN), programmes sur les creneaux du cron** (mardi et vendredi, `publishDate` futur, revele par le cron GitHub Actions). Commit `9a42b5f`.

| Date de publication | Article FR | Categorie | Mot-cle vise |
|---|---|---|---|
| 2026-10-02 | [Smoothie au concombre : eviter l'eau verte](https://www.brunch-story.fr/blog/smoothie-concombre/) | Boissons du matin | `smoothie au concombre` |
| 2026-10-06 | [Bagel saumon avocat : l'ordre de montage](https://www.brunch-story.fr/blog/bagel-saumon-avocat/) | Oeufs et sale | `bagel saumon avocat` |
| 2026-10-09 | [Petit dejeuner japonais : ce qu'il contient](https://www.brunch-story.fr/blog/petit-dejeuner-japonais/) | Organiser un brunch | `petit dejeuner japonais` |
| 2026-10-13 | [Petit dejeuner sportif : avant ou apres](https://www.brunch-story.fr/blog/petit-dejeuner-sportif/) | Petit dejeuner sain | `petit dejeuner sportif` |
| 2026-10-27 | [Petit dejeuner espagnol : la realite](https://www.brunch-story.fr/blog/petit-dejeuner-espagnol/) | Organiser un brunch | `petit dejeuner espagnol` |

`recette brioche tressee` (2026-10-16) sautee : elle double `/blog/recette-brioche-a-l-ancienne/`. Laissee `todo`, en attente d'arbitrage.

## Semaine du 2026-10-04

**Lot A, redige dans la nuit du 3 au 4 octobre et finalise le 4** : 2 articles (FR + EN), programmes sur leurs `scheduled_date`.

| Date de publication | Article FR | Categorie | Mot-cle vise | Volume |
|---|---|---|---|---|
| 2026-10-20 | [Cocktail mimosa : champagne et jus](https://www.brunch-story.fr/blog/cocktail-mimosa/) | Boissons du matin | `cocktail mimosa champagne jus d'orange` | 600 |
| 2026-10-23 | [Origine du bagel : Pologne, pas Vienne](https://www.brunch-story.fr/blog/origine-du-bagel/) | Oeufs et sale | `origine du bagel` | 880 |

Versions EN : `/en/blog/mimosa-cocktail/`, `/en/blog/bagel-origin/`. 3 liens internes par article, tous vers des articles de date anterieure.

**Image du mimosa remplacee au controle visuel** : la premiere photo retenue (Pexels `10594799`) montrait des flutes de rose clair avec des mures, pas un mimosa, qui est opaque et orange ; la seconde (`9228135`) un jus d'orange verse dans un bocal. Retenue : Pexels `1772974`, une vraie flute de mimosa. Les deux rejets sont inscrits au registre `hero-sources.json` sous `_rejet-visuel-mimosa-*`.

**Lot B, produit le 4 octobre** : 5 articles (FR + EN), programmes sur leurs `scheduled_date`. Maillage croise dans le lot, uniquement du plus recent vers le plus ancien.

| Date de publication | Article FR | Categorie | Mot-cle vise | Volume |
|---|---|---|---|---|
| 2026-10-30 | [Calories d'un cafe au lait : le vrai calcul](https://www.brunch-story.fr/blog/calories-cafe-au-lait/) | Petit dejeuner sain | `calories d'un cafe au lait` | 1 300 |
| 2026-11-03 | [Pain perdu recette ancienne : la methode](https://www.brunch-story.fr/blog/pain-perdu-recette-ancienne/) | Pancakes et sucre | `pain perdu recette ancienne` | 2 000 |
| 2026-11-06 | [Smoothie sans lait : le liquide et le cremeux](https://www.brunch-story.fr/blog/smoothie-sans-lait/) | Boissons du matin | `smoothie sans lait` | 400 |
| 2026-11-10 | [Tartine salee : 8 recettes et le bon pain](https://www.brunch-story.fr/blog/tartine-salee-recette/) | Oeufs et sale | `tartine salee recette` | 880 |
| 2026-11-17 | [Porridge aux graines de chia : la recette](https://www.brunch-story.fr/blog/porridge-graines-de-chia/) | Petit dejeuner sain | `porridge aux graines de chia` | 390 |

Versions EN : `/en/blog/cafe-au-lait-calories/`, `/en/blog/traditional-french-toast/`, `/en/blog/dairy-free-smoothie/`, `/en/blog/savoury-toast-recipes/`, `/en/blog/chia-seed-porridge/`. 4 a 5 liens internes par article.

**Garde-fou anti-cannibalisation** : `petit dejeuner au lit` (2026-11-13) sautee et laissee `todo`, elle double `/blog/plateau-petit-dejeuner/` qui porte deja le tag, une FAQ et un H2 « Le plateau au lit ». `recette brioche tressee` toujours en attente. Juges non cannibalisants apres lecture : `pain perdu recette ancienne` contre `pain-perdu-sans-oeuf` (variante a contrainte, autre SERP), `porridge aux graines de chia` contre `bienfaits-graines-de-chia` (recette contre nutrition, l'article bienfaits ne donne qu'un pudding en un paragraphe), `smoothie sans lait` et `tartine salee recette` contre leurs articles generiques voisins. **Risques a venir dans la roadmap, non traites** : `pain perdu avec du pain dur` (2027-01-19) recouvre largement la recette ancienne, qui repose sur le pain rassis ; `porridge recette rapide` (2027-01-08) recoupe le porridge chia ; `levain pour brioche` (2026-11-20) est a relire contre la brioche a l'ancienne.

**Images : 4 rejets sur 9 candidats** (cafe a la creme fouettee, pain perdu de restaurant aux fruits rouges, milkshake rose pour un smoothie sans lait, tartine fromage et confiture). Toutes les photos retenues ont ete choisies sur la liste des candidats Pexels ou Commons, apres controle visuel, et non sur le premier resultat du script.

**Piege** : les recettes EN ne sont pas sous `/en/recettes/` mais sous `/en/recipes/`, via un `url:` force dans leur frontmatter. Un lien ecrit sur le modele FR sort en 404 sans erreur au build.
