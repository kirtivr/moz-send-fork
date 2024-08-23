# What and Why
The main purpose of this repository is to understand how end to end encryption works, and how it can be used in applications. 

# How to run:

## Getting the right NodeJS version

First ensure you have the correct version of node installed. This project uses version 16.13.0.

The best way to ensure the above is to use `nvm`.

[Here](https://www.linode.com/docs/guides/how-to-install-use-node-version-manager-nvm/) is how to install nvm.

Once nvm is installed, and the modified .bashrc is sourced, run:
1. nvm install 16.13.0
2. nvm use 16.13.0

Note: I would be happy to know if there is a way to avoid running nvm.sh upon each boot.

## Running "send"

npm install
npm start

Check that the application runs as expected on http://localhost:8080/.
