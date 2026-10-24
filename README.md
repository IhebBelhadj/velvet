# Velvet

A personal plugin repository for [Playpex Media Server](https://github.com/IhebBelhadj/Playpex), used to try out Playpex's plugin system (signed repository indexes, packages, updates).

## Add it to a server

On the server's dashboard: **Plugins › Repositories › Add repository**, then

```
https://ihebbelhadj.github.io/velvet/index.json
```

Check that the key fingerprint shown is `678d e388 6138 5c7e f0c1 d275 8638 f757`, then **Trust and add**.

## What is here

The repository's signed index (`index.json`, its signature `index.json.sig`) and the packages it lists, built with `npm run pack:repository`. Servers check the index against the key they trusted, and each package against its sha256.

## Note

An educational project. Streaming copyrighted content via torrents may be illegal where you live.
