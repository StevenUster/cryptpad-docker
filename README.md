# Cryptpad docker compose for running via Coolify

## Disable guest access

To disable unregistered use of CryptPad, add the following to customize/application_config.js:

```js
AppConfig.registeredOnlyTypes = AppConfig.availablePadTypes;
```
