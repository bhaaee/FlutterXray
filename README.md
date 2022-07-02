# FlutterXray
FlutterXray, golang, xray core Initial commit of project structure, license, and readme.

#init go.mod

```

go mod download

```

# compolie to .aar library for android

```

gomobile bind -v -o flutterxray.aar -target=android ./

```

# compolie to .framework library for ios

```

gomobile bind -v -o flutterxray.framework -target=ios ./

```
