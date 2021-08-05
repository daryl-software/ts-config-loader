# ts-config-loader

Usage
```typescript
const config = new ConfigLoader([`directory/base.json`, `directory/env-override.json`], { verbose: true });
const dbConfig = config.get<{ db: { host: string; port: number, password?: string }[] }>('db');
```
