# atm_firmware
### Flashing Photon
Compiling and flashing remotely

```sh
$ particle flash <PARTICLE_NAME> <DIR>
```

### Terminal utils
Use `netcat` to test simple server communcation

```sh
$ netcat <IP_ADDRESS> <PORT> <MESSAGE>
```

Use cURL to simulate SMS messages

```sh
$ curl -X POST localhost:4000/sms --data 'From=+4477000000000&Body=EC2A 3AR'
```

### Photon Device Modes
https://docs.particle.io/guide/getting-started/modes/core/

### Setup WiFi via USB
Please note, the particle **can't** connect to 5GHz networks and only supports 2.4GHz

```
particle serial wifi
```
