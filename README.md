# a2a-types

A tiny TypeScript types library containing Google's official A2A (Agent2Agent) types, directly from <https://github.com/google-a2a/A2A/tree/main/types>

## Installation

```bash
npm install -D a2a-types
```

## Usage

```typescript
import type { AgentCard } from "a2a-types";
```

## Updating Types

To pull the latest types from Google's A2A repository:

```bash
npm run update-types
```

This fetches the latest types from:
https://raw.githubusercontent.com/google-a2a/A2A/refs/heads/main/types/src/types.ts

## Contributing

PRs are welcome! This library aims to stay in sync with Google's official A2A types.

## License

Apache-2.0 - from Google's A2A repository
