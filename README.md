# MQTT Garage Door Opener Example Application

A sample application built that shows how MQTT could be used to manage a garage door system by [Charlie Key](https://github.com/zwigby)

For optimal testing make sure that the controller is started first and then immediately after the garage.

##run mqtt container 

docker run -it -p 1883:1883 -p 9001:9001 -v mosquitto.conf:/mosquitto/config/mosquitto.conf eclipse-mosquitto

## Usage

```
npm install
```

### For style checking

```
npm run style
```
