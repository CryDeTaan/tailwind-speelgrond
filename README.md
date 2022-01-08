# Tailwind Speelgrond
A simple Tailwind speelgrond(playground) or starting point for simple HTML pages.

All the tailwindcss assets are compiled using the tailwind-cli.

--- 
## Development

```bash
# Clone repo
git clone https://github.com/CryDeTaan/tailwind-speelgrond.git

# Install dependencies
npm install

# Serve for development environment
npm run serve
```

P.S. Develop in the `/src` directory

P.P.S: Only two additional dependencies are installed and required for the "hot-reloading" experience during development:
- [light-server](https://www.npmjs.com/package/light-server) - A lightweight cli static http server and it can watch files, execute commands and trigger livereload.
- [concurrently](https://www.npmjs.com/package/concurrently) - Run multiple commands concurrently. This runs the tailwind-cli watcher and the `light-server` when `npm run serve` is used which give us this hot-reload experience.

See `packages.json` for more information

## Production

```bash
# Build the assets to the dist directory
npm run build
```
This will publish a directory called `/dist`.

## License
The Tailwind Speelgrond is open-sourced software licensed under the MIT license.

