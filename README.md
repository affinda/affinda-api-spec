Affinda API Specification
===================================

![affinda logo](https://raw.githubusercontent.com/affinda/affinda-python/main/affinda_logo.png)

This repo hosts the API specficiation for the affinda API, used in the generation of the client libaries
by [autorest](https://github.com/Azure/autorest):

- https://github.com/affinda/affinda-python
- https://github.com/affinda/affinda-typescript
- https://github.com/affinda/affinda-java
- https://github.com/affinda/affinda-csharp

It conforms to the [OpenAPI 3.0 specification](https://swagger.io/specification/).

### Updating the spec

Note that the `api_spec_bundled.yaml` and `api_spec_with_examples.json` files are generated dynamically, and should not
be edited manually!

After editing spec, run `../client_libraries/gen_api_clients_and_docs.sh` before committing to regenerate these files.


