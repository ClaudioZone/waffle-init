# Getting started with Waffle's and so on
This little repo hels you to kickstart a smart contract project with waffle's for solidity and yarn/npm for solid testing.

If mainly follow's the waffle's guidline and adds a few lines.

# Resources : 
* https://getwaffle.io/
* https://ethereum-waffle.readthedocs.io/en/latest/start.html#installation
* https://github.com/EthWorks/Waffle --> Full explanation in readme.md !

# $ Commands
~~~~
yarn add ethereum-waffle
# creating test contracts and test test from the resource #2
yarn add openzeppelin-solidity -D
yarn add mocha -D
yarn add chai -D

npx waffle
npx waffle config.json //--> create the config.json with waffle readme content first

mocha #-- or yarn mocha ??

# add waffle && mocha to scripts in package.json
yarn test

yarn add lint -D
yarn lint
~~~~
