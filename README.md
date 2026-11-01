# ORBITE client light

Créé par **GIGACRMANTHE**.

[Installer ORBITE client light](https://raw.githubusercontent.com/GIGACRMANTHE/orbite-client-light/main/ORBITE-client-light.user.js)

1. Installe Tampermonkey dans ton navigateur.
2. Ouvre le lien ci-dessus et clique sur **Installer** dans Tampermonkey.
3. Désactive les autres scripts ORBITE et recharge Starblast.io.

Les fonds, images ECP et textures sont inclus dans le fichier. Aucun serveur ORBITE, compte, clé ou import de pack n'est nécessaire. Starblast utilise sa connexion habituelle.

Bouton **ORBITE** en bas à droite. **F8** active ou désactive les modifications locales.

Pas de chat communautaire ni de gros modèles 3D de décor dans cette édition. Les tests de démarrage autonome et d'intégrité des images sont passés ; la fluidité en partie dépend de la machine.

Voir [les crédits des ressources](CREDITS-ressources.md).

Version 1.1.0 : menu ORBITE, panneaux translucides, couleurs selon le fond, chargement animé et classement aux trois premières places distinctes. Les commandes restent celles du jeu. F8 rétablit la présentation native. Le rendu en partie reste à vérifier sur le navigateur utilisé.

Version 1.2.0 : console de menu latérale, suppression des liens sociaux/musique et entraînement, chargement compact, jauges continues, radar translucide conservant ses contacts, rochers minéraux, gravures dorées et énergie cosmique au contact de la coque. Tous les changements restent locaux et réversibles avec F8. Aucun bonus de bouclier : l'effet est décoratif.

Version 1.3.0 : menu et chargement recentrés, HUD compact translucide, nom de partie au-dessus du radar masqué, coques brillantes. Chat : cinq emotes par phrase ; F9 ajoute une emote vide via le chat natif (validation serveur à confirmer en partie).

Version 1.4.0 : menu, chargement et écrans de mort harmonisés sans panneau opaque imbriqué. HUD et radar simplifiés, reflets nacrés animés sur les coques. La touche E remplace F9 pour l'emote vide, hors saisie de texte. Les tests locaux passent ; le rendu et la réception des emotes restent à confirmer en partie.
Version 1.5.0 : largeur du logo corrigée, panneau après la mort et boutons adaptés aux petites fenêtres, champ du pseudo compact, typographie et finitions dorées harmonisées. Motifs distincts pour nacre, prisme, circuit, givre, magma et obsidienne. Compatibilité des maillages anciens et détection des rochers corrigées. Aperçu rafraîchi après application des choix ; lasers nacrés conservant leur silhouette native et les tirs de soin. Tests locaux réussis, validation visuelle en partie encore nécessaire.
Version 1.6.0 : correction du retour des skins ORBITE vers les matériaux officiels et des aperçus réutilisant une ancienne sélection. Flèches à largeur fixe, titres tronqués proprement et sélecteur ORBITE synchronisé. Changer de skin ne recharge plus le fond du menu. Deux coques supplémentaires (Rails photoniques, Solaire blindé), effets propres aux familles de skins : rails lumineux, circuits, nacre, fissures de magma, givre, veines végétales et reflets dorés discrets. Test de régression : 120 transitions entre skins dans les deux sens et retour au matériau natif. Rendu en partie à confirmer.

Version 1.7.0 : collection de matières seules. Suppression des effets de coque et bandes laser. Nacre, stellaire, graphite mat, laque, opale, or poli et couleurs intenses ; brillance et émission différenciées. Reflets dépendants du matériau natif. Tests locaux réussis ; rendu en partie non vérifié.

Version 1.8.0 : skins et bases séparés. Les flèches officielles sélectionnent la base native sans retirer le skin. Choisir le skin dans ORBITE, puis changer la base dans la personnalisation officielle. Les réglages de brillance sont relatifs au matériau de base. Aperçu et partie utilisent le même choix natif. Tests locaux réussis ; rendu en partie à confirmer.
Toutes les bases deviennent brillantes avec un skin ORBITE, y compris les matériaux natifs sans reflets. Conversion locale en matériau réfléchissant, restaurée avec F8 ; graphite verni et céramique émaillée remplacent les finitions mates.

Version 1.9.0 : rochers à veines minérales, réacteurs à dégradé, cinq tirs supplémentaires (Lance stellaire, Orbe nova, Cristal nacré, Double ion, Comète ambrée), éclats d’impact, RCS compact et nom du système masqué. Effets appliqués aux matériaux natifs, sans modifier les trajectoires ni les dégâts. Tests locaux uniquement ; rendu réel en partie à confirmer.

Version 1.10.0 : huit textures originales brillantes ; flèches officielles parcourant aussi les skins ORBITE. Détection des rochers existants par leur géométrie native, réacteur avec cœur chaud et cellules de pression, impacts sans anneaux. Tests locaux réussis ; rendu en partie à confirmer.

Version 1.11.0 : icônes de chat vectorielles colorées (écusson, éclair, couronne, étoile, robot, cristal, ailes et insigne). Remplacement local des dessins dans le sélecteur et les bulles, libellés et messages natifs conservés. Les joueurs sans ORBITE voient les émotes originales.

Version 1.11.1 : correction du scanner d’émotes qui pouvait appeler des accesseurs natifs et interrompre le démarrage du rendu. Isolation des erreurs d’émotes ; suppression du tutoriel gris au chargement.

Version 1.12.0 : radar biseauté cyan-violet inspiré des émotes, contacts natifs conservés. Lasers plus fins et moins lumineux. Suppression du plafond de 96 rochers qui pouvait être occupé par le décor du menu ; habillage de surface sans aura additionnelle. Validation visuelle en partie encore nécessaire.

Version 1.13.0 : palettes encre et nacre ; panneaux encre et nacre, radar gradué. Branchement direct sur le groupe de rochers du terrain, y compris les objets créés avant le client. Tests locaux ; rendu en partie à confirmer.


Version 1.14.0 : thèmes Émeraude, Nacre, Clair de lune et Braise. Surfaces communes pour les panneaux natifs, classement avec ornements de plumes gravées pour les trois premiers, radar gradué, menus harmonisés. Suppression du redimensionnement des panneaux pour conserver les coordonnées cliquables. Tests locaux réussis ; rendu en partie non vérifié.


Version 1.14.1 : rafraîchissement des panneaux RCS et missiles déjà en mémoire, dessin dédié du RCS et surfaces des missiles. Le matériau de coque sélectionné est aussi appliqué au matériau ECP avant son symbole natif, silhouette conservée. Tests ciblés réussis ; rendu réel en partie à confirmer.

Version 1.15.0 : dix bases optiques propres aux skins (nacre, stellaire, opale, volcanique, obsidienne, mercure, opaline, nébuleuse, onyx et cristal). Les autres finitions conservent une part du motif officiel. Matières précalculées, couleurs d’équipe et géométrie préservées. Tests locaux ; rendu en partie à confirmer.

Version 1.15.1 : les dix skins à base indépendante utilisent une texture de coque recréée sur toute sa surface, sans masque hérité du matériau officiel. Les cartes de relief et de reflets natives sont retirées pour ces skins puis restaurées à la désactivation. Les deux cases de couleurs d’équipe restent natives. Tests locaux ; rendu en partie à confirmer.

Version 1.15.2 : distribution compactée, commentaires explicatifs retirés et identifiants internes raccourcis. Aucun déchiffrement à l’exécution. Métadonnées Tampermonkey et crédits conservés. Le code exécuté dans le navigateur reste récupérable.

Version 1.15.3 : correction du risque de coque blanchie sur les bases indépendantes : conservation du masque lumineux natif, retrait de l’amplification d’émission et réduction des reflets. Textures personnalisées conservées. Tests locaux réussis ; rendu en partie à confirmer.

Version 1.16.0 : quatre coques complètes Séraphin, Ronin, Abysse et Vector, motifs précalculés sans particules supplémentaires. Panneau compact avec précédent/suivant pour coque, tirs et ECP, sélection clavier conservée. Géométrie du vaisseau inchangée. Tests locaux ; rendu en partie à confirmer.
