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
cd carforyou-example-pkg/pkg
npm link

cd carforyou-listings-web
npm link @carforyou/example

cd carforyou-example-pkg
npm run build
```

## Release a new version
```
npm run release
```
