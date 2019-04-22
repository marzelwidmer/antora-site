# Antora

## Build
```bash
$ antora --clean --pull site.yml
```

## Serve
```bash
$ serve build/site

   ┌───────────────────────────────────────────────────┐
   │                                                   │
   │   Serving!                                        │
   │                                                   │
   │   - Local:            http://localhost:5000       │
   │   - On Your Network:  http://192.168.1.103:5000   │
   │                                                   │
   │   Copied local address to clipboard!              │
   │                                                   │
   └───────────────────────────────────────────────────┘
```

## Deploy
```
$ rm -rf ../marzelwidmer.github.io/site
$ mv build/site/ ../marzelwidmer.github.io/
```
