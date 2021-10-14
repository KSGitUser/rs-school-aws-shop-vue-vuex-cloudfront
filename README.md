Link to S3-website: http://rs-school-vue-application-first-1.s3-website-eu-west-1.amazonaws.com

Link to autodeploy with cloudFront: https://d3pxnv2588b85.cloudfront.net/

# shop-vue-vuex-cloudfront

See `develop` branch for development

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your unit tests

```
npm run test:unit
```

### Run your end-to-end tests

```
npm run test:e2e
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### To deploy to cloudfront:

```npm run client:deploy --aws-profile default
sls client deploy -v --no-config-change --no-policy-change --no-cors-change
npm run cloudfront:invalidateCache

```
