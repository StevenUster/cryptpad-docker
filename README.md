# Cryptpad docker compose for running via Coolify

## Disable guest access

Copy template:

```bash
cp customize.dist/application_config.js customize
```

To disable unregistered use of CryptPad, add the following to customize/application_config.js:

```js
AppConfig.registeredOnlyTypes = AppConfig.availablePadTypes;
```
