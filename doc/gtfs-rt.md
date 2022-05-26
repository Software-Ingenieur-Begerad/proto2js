# gtfs-rt

* further description for gtfs-rt is available on the [gtfs.org](https://gtfs.org/realtime/proto/) website

* check clone [repository](git@github.com:google/transit.git)
```
cd /tmp
git clone git@github.com:google/transit.git
```

* copy proto file into this repository
```
cd transit/gtfs-realtime/proto
cp gtfs-realtime.proto ~/<path>/proto2js/proto/gtfs-rt.proto
```

* compile proto file into js file
```
pbf ./proto/gtfs-rt.proto > ./js/gtfs-rt.js
```
