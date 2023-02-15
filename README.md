# MaybeScooters
ENVIRONMENT INSTRUCTIONS
1. install git 
2. install pipenv: pip install pipenv (nice tutorial re pipenv: https://youtu.be/zDYL22QNiWk)
3. on computer cd to the folder which will contain this project and run: git clone https://github.com/NataKr/MaybeScooters.git
4. create virtual environment from: pipenv install --ignore-pipfile
5. to activate virtual environment: pipenv shell
6. install pre-commit - run from terminal in virtual environment: install pre-commit

ADDITIONAL COMMENTS:
1. to install new package in the invironment - in separate branch: pipenv install <package>
2. some python libraries/modules do not have stubs in mypy => to pass pre-commit hooks need to add after the package name: #type: ignore
example:
import pandas #type: ignore
