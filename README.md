# Restful Go
> Houses Back End Code for REST API written in Go lang

[![Custom Badge](https://img.shields.io/badge/Author-Abhijit%20Kar-brightgreen.svg?style=flat)](http://www.abhijit-kar.com/)
[![MIT licensed](https://img.shields.io/badge/Licence-MIT-blue.svg?style=flat)](https://opensource.org/licenses/mit-license.php)
[![GitHub Pages](https://img.shields.io/badge/Server-GitHub%20Pages-brightgreen.svg?style=flat)](http://www.abhijit-kar.com/swagger-editor/)

### Sign into gcloud
gcloud auth application-default login

### To generate go stub
swagger generate server -t gen -f swagger.yaml --exclude-main -A unite_society

### Dev deploy
CD into Server folder
dev_appserver.py app.yaml

### Prod deplooy
gcloud app deploy --version dev
