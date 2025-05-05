# rd-workflow

rd-workflow mean RedDwarf workflow, this repo defined some workflow that could be reused across some project. When we publish some project to different environment, there will be something common steps like:


* checkout code
* [optional] check the code standard
* [optional] do some test
* build project
* package to image
* push the image to image repo
* deployment the application to cloud
* verify the deployment success or not

this can be defined and reuse across project