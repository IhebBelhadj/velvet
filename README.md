# Velvet

A plugin repository for [Playpex Media Server](https://github.com/IhebBelhadj/Playpex): the plugin **Velvet**, its 18+ section (adult films: a catalog from TMDB studios or ThePornDB, torrent releases ranked by seeders). It is never offered to kids profiles and nothing watched with it is remembered.

## Add it to your server

On the server's dashboard: **Plugins › Repositories › Add repository**, then

```
https://ihebbelhadj.github.io/velvet/index.json
```

Check that the key fingerprint shown is `678d e388 6138 5c7e f0c1 d275 8638 f757`, then **Trust and add**. Install Velvet from **Browse**, then enter a TMDB API key (or a ThePornDB one) in its settings.

## What is here

The repository's signed index (`index.json`, its signature `index.json.sig`) and the packages it lists, built with `npm run pack:repository` from the Playpex source (`plugins/velvet`). Servers check the index against the key they trusted, and each package against its sha256.

## Note

An educational project. Adult content: for adults only. Streaming copyrighted content via torrents may be illegal where you live.
