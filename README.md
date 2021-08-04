## Infusionsoft auth in nodejs

Login in infusionsoft e autorizzazione di token e refreshtoken in Keap


Variabili in .env

PORT= la porta in ascolto di nodejs

CLIENTID= API key da https://keys.developer.keap.com/

CLIENTSECRET= API secret https://keys.developer.keap.com/

CALLBACKURL=URL/auth/infusionsoft/callback

Recarsi nel vostro URL e cliccare Authorize per effettuare il login in infusionsoft

Ogni 6 ore viene invocato il refreshtoken per poter continuare ad usare l'applicazione

## Installazione

### Per [Node.js](https://nodejs.org/)
```shell
npm install
```