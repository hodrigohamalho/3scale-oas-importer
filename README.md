# 3scale OAS Import tool

This is a web tooling to import OAS aka Swagger specifications on 3Scale.

## Install on Openshift

    oc create -f openshift/3scale-oas-importer.json -n openshift 
    oc new-app 3scale-oas-importer

## Running Local

    npm install
    npm start run

