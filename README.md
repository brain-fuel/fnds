# luminix.dev/fnds

A wrapper around window, document, event, etc. to be called from BEAM languages.
This library acts as a Functional DOM Shim.

This project uses [Bun](https://bun.sh) to build a small JavaScript library.

## Development

Install dependencies:

```bash
bun install
```

Build the library:

```bash
bun run build
```

## Publishing

Make sure the `dist` directory is present and then publish to npm:

```bash
npm publish
```
