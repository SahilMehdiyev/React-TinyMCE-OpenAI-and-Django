PYTHON = python3
VENV = .venv
MANAGE = $(VENV)/bin/python manage.py

run_server:
	$(MANAGE) runserver

shell:
	$(MANAGE) shell

create_superuser:
	$(MANAGE) createsuperuser

run_migrate:
	$(MANAGE) migrate

run_makemigrations:
	$(MANAGE) makemigrations

pre_commit_run:
	pre-commit run --files

install:
	$(PYTHON) -m venv $(VENV) && $(VENV)/bin/pip install -r requirements.txt

.PHONY: run_server create_superuser
.PHONY: run_migrate run_makemigrations
.PHONY: install pre_commit_run shell
