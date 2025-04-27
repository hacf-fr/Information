# How to contribute

You will find in this document some guidelines to contribute to the HACF community
GitHub organization.

## Contributing to official components

For all activities about Home Assistant official components, we suggest to use a
dedicated branch in [the fork hosted within the organization](https://github.com/hacf-fr/home-assistant-core).
This allows sharing the effort between us, having code reviews and advices from
other french speaking developers.

As soon as the updates are mature enough and validated you will be able to create
a PR on the offical repository. You have an example with `meteo_france` et `linky`.
The latest updates have been done here and discussed on the community Discord.

To ease the coordination, please follow the following branch naming rule: `integration_name/new_feature`

## Hosting source code

If you want to share the code of your librairies, custom components or all other
components linked to Home Assitant, you can do it within the organization.

You will benefit from visibility and support from other french speaking developers
to help maintain the components.

Please follow the repository naming rules:

- `integration_name-api`: for Python libraries
- `integration_name-custom`: for custom components
- `card_name-card`: for custom Lovelace cards

## Python Librairies on PyPI.org

Python libraries have to be hosted on [PyPI.org](https://pypi.org) to be used by Home Assistant core.

We recommend adding the [`hacf-fr`](https://pypi.org/user/hacf-fr/) account as co-owner or maintainer to have a backup if the code owner is not available for a long period.

To ease the maintenance of Python modules, we recommend using GitHub Action to check the code and upload automatically new releases on [PyPI.org](https://pypi.org). We recommand as best practice to use the [`cookiecutter-hypermodern-python`](https://github.com/cjolowicz/cookiecutter-hypermodern-python) template which implement popular and modern Python development standards.

## The awesome list

The [Awesome List francophone](https://github.com/hacf-fr/awesome-francophone-home-assistant)
hosted within the organization regroups interresting, awesome and french speaking
resources linked to Home Assistant. The list needs to be regularly updated and improved by all of us.

Please contribute. Detailed instructions are
available in the repository.

## Community promotion

We should not forget to promote the community in repositories we maintain.
We recommend to use the following badges when applicable.

- [![Discord francophone][discord-shield-fr]][discord-fr]: to promote the Discord
- [![Forum francophone][forum-shield-fr]][forum-fr]: to promote the Forum
- [![Awesome francophone][awesome-shield]][awesome-fr]: to promote the awesome list. Mostly if there is an entry in the list related to an HACF repository.

## Language used

English is standard on GitHub.
We recommand to follow this best practice as much as possible.

On the other hand, we have to welcome and be friendly with the French speaking contributors.

It is allowed to prefer French language on repositories related to services or products targeting only francophones
(example [freebox-api](https://github.com/hacf-fr/freebox-api)).
In this case, we have to make this choice visible.

[awesome-shield]: https://awesome.re/badge.svg
[awesome-fr]: https://awesome.hacf.fr
[forum-shield-fr]: https://img.shields.io/discourse/topics?label=Forum%20francophone%20HACF&logo=discourse&server=https%3A%2F%2Fforum.hacf.fr%2F
[forum-fr]: https://forum.hacf.fr/
[discord-shield-fr]: https://img.shields.io/discord/706096417000652840?label=Discord%20francophone%20HACF&logo=discord
[discord-fr]: https://discord.com/invite/PaZFEjX
