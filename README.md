# hass_grdf_api

## Quick start
Clone, then
```shell
pyenv virtualenv 3.11.1 hass_grdf_api
pyenv local hass_grdf_api
pip install pip-tools
pip-sync requirements.txt requirements-dev.txt
pre-commit install --install-hooks
inv test
./src/manage.py migrate
./src/manage.py createsuperuser
```

# Reuse
If you do reuse my work, please consider linking back to this repository 🙂
