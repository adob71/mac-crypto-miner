### Deployment
```
$ launchctl load /Library/LaunchDaemons/local.mac.*
```

#Decomissioning
```
$ launchctl unload /Library/LaunchDaemons/local.mac.*

```

### Project Structure
```
.
|-- LaunchDaemons
|   |-- local.mac.dogecoin.start.plist
|   |-- local.mac.dogecoin.stop.plist
|   |-- local.mac.ethereum.start.plist
|   `-- local.mac.ethereum.stop.plist
|-- README.md
|-- dogecoin
|   |-- start
|   |-- stop
|   `-- xmrig
`-- ethereum
    |-- ethminer-m1
    |-- start
    `-- stop
```
