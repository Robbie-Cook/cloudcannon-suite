<p align="center">
  <img src="logo.svg" />
</p>

<h1 style="font-weight: bold;" align="center">CloudCannon Suite</h1>

## Usage

You can find full setup instructions here: 
https://suite.cloudcannon.com/dev/setup/

## Local development
Run `yarn link` in your cloudcannon-suite install folder
Run `yarn link @cloudcannon/suite` in any repo to create a symlink to the local suite

## Deploying a new version

```
$ npm version 1.1.7
...

$ git push
...

$ npm publish
...
```