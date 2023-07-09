# Parse ezkl proofs in TS for front end applications.

The helper function in scripts/parse-proof.ts enables users to parse EZKL proofs into `publicInputs` and `proof`, the two
parameters EZKL verifiers accept as input.

To run the script 

1) install dependencies:

```shell
npm install
```

2) boot up a local hardhat node

```shell
npx hardhat node
```

3) Run the script :) 

```shell
npx hardhat run --network localhost scripts/parse-proof.ts
```
