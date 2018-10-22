# 3scale OAS Import tool

This is a web tooling to import OAS aka Swagger specifications on 3Scale.

![](docs/oas-importer.png)

Currently it import:

* API definition

![](docs/metadata.png)

* Mapping Rules 

![](docs/mapping-rules.png)

* Methods

![](docs/methods.png)

* ActiveDocs (Swagger 2.0)

![](docs/activedocs.png)

## Install on Openshift

Import the template

    oc create -f openshift/3scale-oas-importer.json -n openshift 

Create the app

    oc new-app 3scale-oas-importer

## Running Local

    npm install
    npm start run

