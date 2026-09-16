# Python I2C Driver for Sensirion SBN4X

This repository contains the Python driver to communicate with a Sensirion SBN4x sensor over I2C.

<img src="https://raw.githubusercontent.com/Sensirion/python-i2c-sbn4x/master/images/product_image.jpg"
    width="300px" alt="SBN4X picture">


Click [here](https://sensirion.com/products/product-categories/) to learn more about the Sensirion SBN4x sensor.



The default I²C address of [SBN4x](https://sensirion.com/products/catalog) is **0x20**.



## Connect the sensor

You can connect your sensor over a [SEK-SensorBridge](https://developer.sensirion.com/product-support/sek-sensorbridge/).
For special setups you find the sensor pinout in the section below.

<details><summary>Sensor pinout</summary>
<p>
<img src="https://raw.githubusercontent.com/Sensirion/python-i2c-sbn4x/master/images/product_pinout.jpg"
     width="300px" alt="sensor wiring picture">

| *Pin* | *Cable Color* | *Name* | *Description*  | *Comments* |
|-------|---------------|:------:|----------------|------------|
| 1 | green | SDA | I2C: Serial data input / output |
| 2 | black | GND | Ground |
| 3 | yellow | SCL | I2C: Serial clock input |
| 4 | red | VDD | Supply Voltage | 4.9V to 5.5V


</p>
</details>


## Documentation & Quickstart

See the [documentation page](https://sensirion.github.io/python-i2c-sbn4x) for an API description and a
[quickstart](https://sensirion.github.io/python-i2c-sbn4x/quickstart.html) example.


## Contributing

In case you want to contribute to this project, please read the [contribution guidelines]((https://sensirion.github.io/python-i2c-sbn4x/contributing.html)).

## License

See [LICENSE](LICENSE).