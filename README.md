# TSConfig base

Hosts TSConfig base that I personally use for my TS projects. 
The base has very strict rules, that drive strictly typed, good quality code. 

## How to use

Install:

```sh
# npm installation
npm install --save-dev @bozerkins/tsconfig-base

# yarn installation
yarn add --dev @bozerkins/tsconfig-base
```

Add to your `tsconfig.json`:

```json
"extends": "@bozerkins/tsconfig-base/tsconfig.json"
```

## Example tsconfig.json

```json
{
  "extends": "@bozerkins/tsconfig-base/tsconfig.json",
  "compilerOptions": {
    "baseUrl": "./",
    "module": "ES2022",
    "moduleResolution": "Node",
    "target": "ES2022"
  }
}
```
