---
"@collana-solutions/next-with-google-secrets": major
---

The package is now published as `@collana-solutions/next-with-google-secrets`. The API is unchanged. To migrate, replace the old package with the new one:

```shell
npm uninstall @neolution-ch/next-with-google-secrets
npm install @collana-solutions/next-with-google-secrets
```

Then change the import in `next.config.js`:

```js
const { withGoogleSecrets } = require("@collana-solutions/next-with-google-secrets");
```

`@neolution-ch/next-with-google-secrets` gets deprecated and receives no further releases.
