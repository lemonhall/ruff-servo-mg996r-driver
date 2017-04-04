# MG-996R Driver

Servo MG-996R 's Driver description if have.

## Device Model

- [{MG-996}](https://rap.ruff.io/devices/{MG-996})

> You can name {device-model} by {model-name} like gy-30 or {chip-name}-({interface}) like ssd1306-i2c.

## Install

```sh
> rap device add --model {MG-996} --id <device-id> 
```

## Demo

Supposed device-id is `mg996` in the following demos.

```js
$('#mg996').setAngle();
```

> It will be better if you attach some pictures of your device demo.**

<div align="center">
<img src="https://rap.ruff.io/api/devices/MG-996/image?1491288130039" width = "391" height = "203" alt="device demo" />
</div>

## API References

### Methods

#### `setAngle()`

The function of method setAngle().

### Properties (opt.)
0~180 angle, some of modle has max 360

### Events (opt.)

## Supported OS

Test passed on Ruff v1.7.2 

## Note

Some notes about device or driver if have.
