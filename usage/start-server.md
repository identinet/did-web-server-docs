# Start Server



1. Create a DID for the server's owner, e.g. a `did:key` DID as shown below
2. Set other configuration parameters and start the service, e.g.:

```
mkdir /tmp/did_store
didkit key generate ed25519 > owner.jwk

DID_SERVER_OWNER="$(didkit key-to-did -k owner.jwk)" \
DID_SERVER_EXTERNAL_HOSTNAME=example.com \
DID_SERVER_EXTERNAL_PORT=3000 \
DID_SERVER_EXTERNAL_PATH=/dids \
DID_SERVER_BACKEND=file \
DID_SERVER_BACKEND_FILE_STORE=/tmp/did_store ./did-web-server
```
