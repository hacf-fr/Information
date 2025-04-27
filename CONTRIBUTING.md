# Comment contribuer

_For English speaking visitors. The contributing guidelines are available in your language: `CONTRIBUTING_EN.md`._

Vous trouverez dans ce document des conseils et bonnes pratiques pour contribuer
dans l'organisation GitHub de la communauté HACF.

## Contribuer aux composants officielles

Pour toutes activités sur les composants officiels de Home Assistant, nous recommandons l'utilisation du [fork hébergé dans l'organisation](https://github.com/hacf-fr/home-assistant-core) dans
des branches dédiées. Cela permettra de partager l'effort, d'avoir des revues
et des conseils d'autres développeurs francophones.

Une fois les modifications matures et validées vous pourrez alors créer une PR
sur le dépôt officiel de Home Assistant. Vous avez un exemple avec `meteo_france` et `linky` dont les dernières modifications
ont été construites ici et discutées sur le Discord de la communauté.

Pour faciliter la coordination, veuillez respecter la convention suivante pour
nommer vos branches: `nom_de_l_integration/nom_nouvelle_fonction`.

## Hébergement des sources

Si vous voulez partager le code source de vos librairies, de vos custom components
ou tout autre élément liés à Home Assistant, vous pouvez le faire ici.

Cela permettra de donner de la visibilité, et de bénéficier du support d'autres
développeurs actifs et francophones pour aider à maintenir ces composants.

Nous vous demandons de suivre la règle de nommage suivant pour vos dêpots:

- `nom_de_l_integration-api`: pour les librairies Pythons
- `nom_de_l_integration-custom`: pour les custom_components
- `nom_de_la_carte-card`: pour les cartes Lovelace

## Librairies Python sur PyPI.org

Les librairies Python doivent être hébergées sur [PyPI.org](https://pypi.org) pour être utilisable avec Home Assistant core. 

Nous recommandons d'ajouter le compte [`hacf-fr`](https://pypi.org/user/hacf-fr/) en co-owner ou en maintainer pour avoir un backup si le code owner est indisponible pendant une longue durée.

Pour faciliter la maintenance de ces modules Python, nous recommandons d'utiliser les GitHub Action pour automatiser les vérifications de code et l'upload d'une nouvelle version sur [PyPI.org](https://pypi.org). Une bonne pratique consiste à utiliser le template [`cookiecutter-hypermodern-python`](https://github.com/cjolowicz/cookiecutter-hypermodern-python) qui implémente déjà les standards populaires et modernes du développement Python.

## L'Awesome list

L'[Awesome List francophone](https://github.com/hacf-fr/awesome-francophone-home-assistant)
hébergée dans l'organisation est là pour regrouper toutes les ressources interressantes liées à Home Assitant
pour les francophones. Elle doit être vivante et peut être améliorée par tous.
N'hésitez pas à contribuer. Des instructions détaillées sont disponible dans le
dépôt.

## Promotion de la communauté

N'oublions pas de faire la promotion de la communauté dans les dépôts que nous maintenons.
Nous recommandons d'utiliser quand cela est pertinent les badges suivants:

* [![Discord francophone][discord-shield-fr]][discord-fr]: pour la promotion du Discord
* [![Awesome francophone][awesome-shield]][awesome-fr]: pour la promotion de l'awesome list. Surtout s'il y a une entrée dans la liste en lien avec un dépôt HACF

## Language utilisée

Sur GitHub, la langue préconnisée est l'anglais. Nous recommandons de suivre cette bonne pratique autant que possible.

En revanche, nous devons être accueillant et bienveillant quand des francophones viennent contribuer en français sur les dépôts de la communautés.

Nous pouvons aussi priviliégier le français sur certains dépôts, qui sont reconnus pour n'adresser qu'une population cible francophone (example [freebox-api](https://github.com/hacf-fr/freebox-api)).
Dans ce cas, il faut l'afficher de manière explicite.

[awesome-shield]: https://awesome.re/badge.svg
[awesome-fr]: https://awesome.hacf.fr
[forum-fr]: https://forum.hacf.fr/
[discord-shield-fr]: https://img.shields.io/discord/706096417000652840?label=Discord%20francophone%20HACF&logo=discord
[discord-fr]: https://discord.com/invite/PaZFEjX
