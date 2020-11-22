## Steps

## npm init

## npm i @nlpjs/basic @nlpjs/express-api-server @nlpjs/directline-connector

 get corpus here : curl -O https://raw.githubusercontent.com/axa-group/nlp.js/master/examples/03-qna-pipelines/corpus.json

 make file conf.json : 

 {

  "settings": {

    "nlp": {

      "corpora": ["./corpus.json"]

    },

    "api-server": {

      "port": 3000,

      "serveBot": true

    }

  },

  "use": ["Basic", "ExpressApiServer", "DirectlineConnector"]

}

run index.js