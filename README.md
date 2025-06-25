Test for deployment of Vitrina stare.js FE and BE + MongoDB

It follows the ansible template made on https://github.com/infra-sandbox/deployment-kit
with slight changes to the python tasks to accomodate the use of ubuntu 24.04, which natively
uses python 3.12. This changes are necessary in order for it to work and depend on installing
python 3.10 and making a venv with it.
