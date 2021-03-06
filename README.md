# practice.automationtesting - My pet_project for studying pytest, sellenium, allure and loguru
# TestCases you can see on the page http://practice.automationtesting.in/test-cases/

## Requirements:
* python 3.10 or latest
* Install all dependencies: "pip install -r requirements.txt"

## Run tests:
* Run one test: "pytest tests/<module_name>/<test_name>"
* Run all tests: "pytest tests/"
* Run using pytest-xdist: "pytest -n <n>"

## Allure reports:

* Save test results in allure: "--alluredir=allure_results"
* Clear allure results of previous test run: "--clean-alluredir"
* Generate allure report: "allure serve allure_results/"

## PRE-COMMIT
* Run command: pre-commit install
* Now every time you commit your code, pre-commit will check
for the rules described in the '.pre-commit-config.yaml' file
* If you want to check you code without commit, run command: "pre-commit run --all-files"
