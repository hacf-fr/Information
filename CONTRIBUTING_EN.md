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

We are hosting [a GitHub project](https://github.com/hacf-fr/home-assistant-core/projects/1)
to collect ideas or bugs for the integration we are working on. If you want to
contribute to an already identified action, go on, create your branch, code and ask
for advice to the community.

## Hosting source code

If you want to share the code of your librairies, custom components or all other
components linked to Home Assitant, you can do it within the organization.

You will benefit from visibility and support from other french speaking developers
to help maintain the components.

Please follow the repository naming rules:

- `integration_name-api`: for Python libraries
- `integration_name-custom`: for custom components
- `card_name-card`: for custom Lovelace cards

## Python Modules on PyPI.org

Python libraries have to be hosted on [PyPI.org](https://pypi.org) to be used by Home Assistant core.

We recommend adding the [`hacf-fr`](https://pypi.org/user/hacf-fr/) account as co-owner or maintainer to have a backup if the code owner is not available for a long period.

To ease the maintenance of Python modules, we recommend using GitHub Action to upload automatically new releases on [PyPI.org](https://pypi.org).

## The awesome list

The [Awesome List francophone](https://github.com/hacf-fr/awesome-francophone-home-assistant)
hosted within the organization regroups interresting, awesome and french speaking
resources linked to Home Assistant. The list needs to be regularly updated and improved by all of us.

Please contribute. Detailed instructions are
available in the repository.
