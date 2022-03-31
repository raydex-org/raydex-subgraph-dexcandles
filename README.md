# Ray Dex Subgraphs

Subgraph for Ray Dex on PulseChain.

### Setup

```
# Install dependencies (yarn or npm)
$ npm install

# Generate types constants
$ npm run codegen

# build subgraph
$ npm run build

```

### (README)

Deliver analytics & historical data for Ray Dex.
The Graph exposes a GraphQL endpoint to query the events and entities within the RayDex ecosytem.

## Deploy

For any of the subgraphs:

1. npx graph create <username>/<subgraph-name> --node <graph-node>
2. npx graph deploy <username>/<subgraph-name> --ipfs <ipfs-url> --node <graph-node>
