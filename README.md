# FullStackFioriApp_CAPModel
Full Stack Fiori Application using CAP Model

## Commands

`mbt build` -> to build mta.yaml

`cf deploy /home/user/projects/e_Learning/mta_archives/e_Learning_1.0.0.mtar` -> to deploy e_Learning_1.0.0.mtar

`cds bind -2 e_Learning-db:SharedDevKey` -> to bind HDI container

`cds watch --profile hybrid` -> to deploy locally

### CoverageTest

`npm install --save-dev nyc qunit` -> to install nyc and qunit dependencies

`npm run coverage` -> to check coverage
