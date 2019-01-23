# Teachable TSLint Config

This is a shared configuration of TSLint for Teachable apps:

How-To
======
1. `yarn add --dev @teachable/tslint-config`
2. Extend from it in `tslint.json`:
```javascript
{
  "extends": "@teachable/tslint-config"
}
```

To deploy:
=========

 `npm version minor` (please follow semver)
