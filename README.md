# pigpio-vma309
Sound Sensor VMA309 for Raspberry Pi using npm module **pigpio**.

![alt text](./images/vma309.jpg)

## Installation
	$ npm install pigpio-vma309 --save



## Usage
````javascript
var Sensor = require('pigpio-vma309');
var sensor = new Sensor({pin:19});

sensor.on('alert', (duration) => {
    console.log('Sound detected for %d milliseconds', duration);
});
````
