# Kitchen Sink Demo

## What's Included?

Demo blocklet that showing how to define a blocklet:

- Meta, checkout [blocklet.yml](./blocklet.yml)
- Interfaces: checkout [app/index.js](./app/index.js)
- Hooks: checkout [app/hooks](./app/hooks)

## Requirements

- Node.js v12.x or above
- A running ABT Node instance on dev environment

## Getting Started

### 1. Install ABT Node

```shell
npm install -g @abtnode/cli
```

### 2. Get the Blocklet

```shell
git clone https://github.com/blocklet/kitchen-sink-demo.git
cd kitchen-sink-demo
npm install # or yarn
```

### 3. Setup the node

```shell
abtnode init -f
abtnode start
```

> The ABT Node instance is stored under the `.abtnode` directory.

### 4. Deploy the Blocklet

```shell
npm run deploy
```

> The blocklet is bundled under the `.blocklet` directory

Then checkout the blocklet in your ABT Node Dashboard.
