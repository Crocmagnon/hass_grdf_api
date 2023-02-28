# Home Assistant GRDF API
Offer home automations platforms a way to access their French gas usage. Thus, the rest of this readme will be mostly in French 🙂

Proposer aux utilisateurs de plateformes domotiques un moyen d'accéder à leur consommation GRDF.

Cible : Home Assistant (dans un premier temps au moins).

Moyens :

- Service web
- Intégration Home Assistant

Le service web fait office de passe plat API et permet de collecter les différents consentements auprès des utilisateurs.

L'intégration Home Assistant récupère les données du passe plat et les expose à l'API énergie.

## Quick start
Clone, then
```shell
pip install -U pip-tools invoke
inv sync-dependencies
pre-commit install --install-hooks
inv test
./src/manage.py migrate
./src/manage.py createsuperuser
```

# Reuse
If you do reuse my work, please consider linking back to this repository 🙂

Si vous réutilisez mon travail, merci de considérer un lien vers ce repository 🙂
