pylint:
	poetry run pylint . main.py

isort:
	poetry run isort .

black:
	poetry run black .

fmt: isort black

test:
	poetry run pytest

clean: ## Remove __pycache__ folders
	@find . | grep __pycache__ | xargs rm -rf
