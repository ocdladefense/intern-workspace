# intern-workspace
Workspace for developing intern packages.

## Example
https://appdev.ocdla.org/intern-workspace/examples/webc-ors.html

## Installation
After cloning:
Run git submodule update --init --recursive

This should download all of the git submodules development branches.

Then run:
npm update

git submodule add -b development --name webc-ors https://github.com/ocdladefense/webc-ors.git dev_modules/webc-ors
git submodule add -b development --name webc-oar https://github.com/ocdladefense/webc-oar.git dev_modules/webc-oar
git submodule add -b development --name webc-events https://github.com/ocdladefense/webc-events.git dev_modules/webc-events
git submodule add -b development --name node-ors https://github.com/ocdladefense/node-ors.git dev_modules/node-ors
