git remote add upstream https://github.com/ansible/django-ansible-base.git
python -m venv .venv
thinkpad:~/repos/django-ansible-base$ source .venv/bin/activate
pip install build
make build
make help
make postgres

