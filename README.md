# hyperfuse-proxy

[hyperfuse](https://github.com/mafintosh/hyperfuse) backed filesystem that proxies to a local folder

```
npm install -g hyperfuse-proxy
```

## Usage

``` js
# first install hyperfused and dupsh
# then will proxy ./mountpoint to ./a-local-folder (make sure they exist)
dupsh 'hyperfuse-proxy ./a-local-folder' 'hyperfused ./mountpoint'
```

## License

MIT
