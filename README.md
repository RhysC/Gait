Gait
====

Generate Models and UI components from Swagger REST definitions

Inspired by a conversation with @Chrismckelt wrt to generating ui compinets from Swagger definitions

Basically i would like to generate components at designtime - not runtime - that include
* Ui models with scope for 
  * validation. Genrate what we can (eg required and type safety)
  * loading data and populating the models (including any ref data)
  * sending data with the appropriate verbs payloads and urls (paths based with global overrides for base url)
* View templates

Links
* Existing json schema model to code https://gist.github.com/RhysC/480e7a758639a3215701
* Current swagger schema https://github.com/swagger-api/swagger-spec/blob/master/schemas/v2.0/schema.json
* Issue raised to get Newtonsoft to support draft 4 of json schema https://github.com/JamesNK/Newtonsoft.Json/pull/328
