# CAR FOR YOU Example

## Usage
```
npm install @carforyou/example
```

## Development
```
npm run build
```

You can link your local npm package to integrate it with any local project:
```
cd carforyou-example-pkg
npm run build

cd carforyou-listings-web
npm link ../carforyou-example-pkg/pkg
```

## Release a new version
```
npm run release
```

## Add two commits

But squash them together.

## Circle CI

You will need to enable the repository in circle CI ui to be able to build it.

For slack notifications to work you will need to provide the token in circle settings.
