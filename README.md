# Doxity - Simpleton Version

### Documentation Generator for Solidity Contracts
##### Powered by [Gatsby](https://github.com/gatsbyjs/gatsby)
This project is an attempt to create a working version of the [@digix/doxity project](https://github.com/DigixGlobal/doxity).

Additional assistance in this fix was gleaned from [ProjectWyvern](https://github.com/ProjectWyvern/wyvern-ethereum)

## Getting Started

edit the following files to your desired parameters
- .doxityrc
- package.json

## Load contracts
copy solidity contracts to the contracts folder

## Build the docs

```bash
# clone this repo
git clone https://www.github.com/ryanhendricks/doxity-simpleton.git
# install doxity dependencies
cd doxity
yarn
# return to root dir
cd ..
# install project dependencies from root folder
yarn
# build the docs
doxity build
```


For a more in depth look at how this works and for additional commands please see: [Original Readme](https://github.com/DigixGlobal/doxity/blob/master/README.md)


[Demo Site](https://hitchcott.github.io/doxity-demo/docs/MetaCoin/)
