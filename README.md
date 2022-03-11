# MISP_Maladie_Galaxy
The aim of this project is to classify the diseases, This topic is wide this git is only focusing on listing the different Cancers in the purpose of an integration in MISP 
and hope that it could be used again subsequential for other type of disease which are not implemented.

## JSON creation

The site https://www.webmd.com/cancer/cancer-a-to-z was used as reference for the data of our json
We create all the uuid necessary for our galaxy thanks to https://www.uuidgenerator.net/

Our json classified all the cancer, for each of them we have :
- value : the name of the cancer
- description : a sentence to present it
- ref : url of the article for more details
- uuid : the uuid associated to the cancer

## TO-DO LIST
- [x] Searching cancer information
- [x] Creating a MISP Formated Json
- [X] Check MISP json format
- [ ] Integration to the [MISP project](https://github.com/MISP)
- [ ] End of project

## Contributors
Main contributors : 
- BELHADJ-CHAIDI Badis
- PEDROTTI Thomas

<img src="KrakenAbyssEffect.png" height="200">

MISP Introducers & Project Helpers :
- DULAUNOY Alexandre
- VINOT Raphaël

![MISP Logo](https://upload.wikimedia.org/wikipedia/commons/9/91/Misp-logo.png) \
