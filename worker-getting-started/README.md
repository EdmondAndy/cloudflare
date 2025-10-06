# Cloudflare Worker Getting Started

This repository contains a starter template for building Cloudflare Workers using TypeScript.

## Project Structure

```
worker-getting-started/
├── package.json
├── tsconfig.json
├── vitest.config.mts
├── worker-configuration.d.ts
├── wrangler.jsonc
├── src/
│   └── index.ts
├── test/
│   ├── env.d.ts
│   ├── index.spec.ts
│   └── tsconfig.json
```

## Getting Started

1. **Install dependencies**
   ```zsh
   npm install
   ```

2. **Development**
   - Start the local development server:
     ```zsh
     npm run dev
     ```

3. **Testing**
   - Run tests using Vitest:
     ```zsh
     npm test
     ```

4. **Deploy**
   - Deploy your worker using Wrangler:
     ```zsh
     npm run deploy
     ```

## Configuration
- `wrangler.jsonc`: Wrangler configuration for Cloudflare Workers.
- `tsconfig.json`: TypeScript configuration.
- `vitest.config.mts`: Vitest testing configuration.

## Folder Overview
- `src/`: Source code for the worker.
- `test/`: Test files and environment definitions.

## Resources
- [Cloudflare Workers Documentation](https://developers.cloudflare.com/workers/)
- [Wrangler CLI](https://developers.cloudflare.com/workers/wrangler/)
- [Vitest](https://vitest.dev/)

---

Feel free to modify this template to suit your needs!
