# tiger-king
simple static javascript/Angular webpages

## hosted on 
https://tiger-king.appspot.com

## deploy to app-engine
### pre-requisirtes
```cmd
git clone https://github.com/risheeboy/tiger-king.git
cd tiger-king
```
- create a google cloud project
- get maps API key https://developers.google.com/maps/documentation/javascript/get-api-key and replace in index.html (optional)
- install gcloud https://cloud.google.com/sdk/docs/downloads-interactive 
### steps
```cmd
gcloud app deploy --project <google cloud project name>
```
