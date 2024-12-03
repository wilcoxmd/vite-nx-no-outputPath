# Demo repo for omitting outputPath

This is an example repo to demonstrate that the @nx/vite build executor throws an error when `outputPath` is not provided. 

## Repro steps

Clone this repo, then install dependencies with npm: 

```sh
npm install
```

Try to build the project:

```sh
npx nx build vite-nx-no-outputPath
```

Note the error thrown: 

> The "path" argument must be of type string. Received undefined 