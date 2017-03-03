# json-validator

This a docker image for validating json document using [json-schema](http://json-schema.org/).
It uses [justinrainbow/json-schema](https://github.com/justinrainbow/json-schema).

## Usage

```
docker run -v /path/to/json/files/:/scripts/ texthtml/json-validator json-validator /scripts/path/to/document.json
```
