# AI Software Template

This application, audi, was created from an AI Software Template. These software templates create a new source code repository as well as a new gitops deployment repository.

Included in the source code repository will be the chosen sample source application.

## Sample Source Application

An AI enabled audio transcription streamlit application. Upload an audio file to be transcribed.

## Repositories

The source code for your application can be found in [https://github.com/jrichter-rhtap/moreaudio ](https://github.com/jrichter-rhtap/moreaudio ).
 
The gitops repository, which contains the kubernetes manifests for the application can be found in 
[https://github.com/jrichter-rhtap/moreaudio-gitops ](https://github.com/jrichter-rhtap/moreaudio-gitops ). 

## Application namespaces 

The default application will be found in the namespace: **`rhdh-app`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.