Remember to clone with `--recursive` or run `git submodule update --init`

### Run kaya (Local chain for Scilla)
  - `cd kaya`
  - `npm install`
  - `npm run debug:fixtures`

### Deploy contract from emont-frenzy
  - `cd scripts`
  - `npm install`
  - `node DeployContract.js`

  The contract by default will be deployed at `cef48d2ec4086bd5799b659261948daab02b760d` using the first account `7bb3b0e8a59f3f61d9bff038f4aeb42cae2ecce8`

### Make transaction
  - Import utility functions from `scripts/CreateTransaction.js`
  or
  - Run example with `node CreateTransaction.js`

### Get contract state
  - `node GetState.js`


