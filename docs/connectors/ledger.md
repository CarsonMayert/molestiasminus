# `web3-react` Documentation - Ledger

- [Install](#install)
- [Arguments](#arguments)
- [Example](#example)

## Install
`yarn add @web3-react-wan/ledger-connector`

## Arguments
```typescript
chainId: number
url: string
pollingInterval?: number
requestTimeoutMs?: number
accountFetchingConfigs?: any
baseDerivationPath?: string
```

## Example
```javascript
import { LedgerConnector } from '@web3-react-wan/ledger-connector'

const ledger = new LedgerConnector({ chainId: 1, url: '...' })
```