# 🌍 Deno Site

The first JAMStack static site generator written in Deno, for building fast, beautiful, and accessible documentation sites.

**⚠️ WARNING:** This project is currently in alpha-stage development. Expect breaking changes.

[![Test CI](https://github.com/denorg/site/workflows/Test%20CI/badge.svg)](https://github.com/denorg/site/actions)

```bash
deno run --allow-read --allow-write --allow-net https://raw.githubusercontent.com/denorg/site/master/cli.ts <arguments>
```

Alternatively, you can use the API:

```ts
import { build } from "https://raw.githubusercontent.com/denorg/site/master/mod.ts";

const siteResult = await build();
```

You can also install it globally using the following:

```bash
deno install --allow-read --allow-write --allow-net -n site https://raw.githubusercontent.com/denorg/site/master/cli.ts
```

Then, the package is available to run:

```bash
site <arguments>
```

Required permissions:

1. `--allow-read`
1. `--allow-write`
1. `--allow-net`

## 👩‍💻 Development

Run tests:

```bash
deno test --allow-read
```

## ⭐ Related

- [staart/site](https://github.com/staart/site) is the inspiration for this project

## 📄 License

MIT © [Denorg](https://den.org.in)
