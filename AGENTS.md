# AGENTS.md

## Overview

Bridge UI for transferring tokens between Arianee networks (fork of POA Bridge UI). Allows users to bridge assets between different EVM chains in the Arianee ecosystem.

## Stack

| Layer | Technology |
|-------|-----------|
| Language | JavaScript |
| Framework | React (Create React App) |
| State | MobX |
| Blockchain | ethers / web3 |

## Architecture

```
src/
├── App.js          # Main app
├── components/     # React components
├── stores/         # MobX stores
└── assets/         # Static assets
```

## Dependencies

### Depends on
- Blockchain RPC nodes (source & target chains)
- Bridge smart contracts

## Deployment

Dockerized.

## Development

```bash
npm install
npm run build      # Build
npm run deploy     # Deploy to gh-pages
```

## Ownership

| Role | Team / Person |
|------|--------------|
| Squad | <!-- TODO: needs human input --> |
