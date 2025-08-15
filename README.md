# vite-filesize-visualizer
File visualizer for Vite apps

# Setup
1. Add the content of visualizer() inside the configuration.ts into your existing vite.config.ts file. This part does the magic:
   visualizer({
      filename: "stats.html",
      open: false,
      gzipSize: true,
      brotliSize: true,
    }),
3. Add the stats.html in the root of your project (same path as your vite.config.ts file)
