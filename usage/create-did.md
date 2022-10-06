# Create DID



Either:

* Store valid [DID document](https://w3c.github.io/did-core/#did-documents) in the configured DID store directory, e.g. `./did_store/valid.json`
* (not yet implemented) Or use the admin API endpoint to create a DID, e.g. `curl -X POST -H "Authentication: Bearer XYZ" -d @diddoc.json http://localhost:8000/valid/did.json`
