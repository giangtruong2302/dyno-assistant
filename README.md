# Dyno Assistant

A powerful AI assistant toolkit built on top of Vercel AI SDK. This project is a fork of [OpenAssistant](https://github.com/GeoDaCenter/openassistant) customized for personal use.

## Packages

This monorepo contains several packages:

- `@dyno-assistant/core`: Core functionality for building AI assistants
- `@dyno-assistant/ui`: UI components for chat interfaces
- `@dyno-assistant/utils`: Utility functions used across the project

## Installation

```bash
npm install @dyno-assistant/core @dyno-assistant/ui
```

## Quick Start

```jsx
import { Assistant } from '@dyno-assistant/core';
import { ChatUI } from '@dyno-assistant/ui';

function MyComponent() {
  return (
    <Assistant apiKey={process.env.OPENAI_API_KEY}>
      <ChatUI />
    </Assistant>
  );
}
```

## Development

```bash
# Install dependencies
yarn install

# Build all packages
yarn build

# Watch for changes
yarn watch
```

## License

MIT
