# mqtt-client

## To set up mqtt subscription
```bash
docker run --rm -it andregomars/mqtt-client sh
mqtt sub -t 'mytopic' -h 'test.mosquitto.org' -v
```

## To publish mqtt
```bash
docker run --rm andregomars/mqtt-client mqtt pub -t 'mytopic' -h 'test.mosquitto.org' -p 1883 -m 'from MQTT.js'
```