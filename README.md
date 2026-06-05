# chakurov.dev

Source for my personal portfolio site. Built with [Astro](https://astro.build).

Live: https://chakurov.dev

## Develop

```bash
npm install
npm run dev      # local dev server
npm run build    # produces dist/
```

## Deploy

```bash
tar -czf /tmp/site.tar.gz -C dist .
node /home/rob/deploy-static.js chakurov.dev /tmp/site.tar.gz
```
