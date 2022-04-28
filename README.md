# Cookiecutter for Ansible roles
---------------------------------
## Prereq
----------
A python virtual environment is needed.

```
python3 -m venv .env
source .env/bin/activate
pip install "molecule[lint]" molecule-docker ansible cookiecutter
```

## How to use
-----------
To use, run:

```
cookiecutter https://github.com/dstdev/ansible-role-cookiecutter
```
