# pigpio-vma309
Sound Sensor VMA309 for Raspberry Pi using npm module **pigpio**.

## Installation
	$ npm install pigpio-vma309 --save

## Usage

var sensor = new SoundSensor({pin:19});

sensor.on('alert', (duration) => {
    console.log('Sound detected', duration);
});

````javascript

var Sensor = require('pigpio-vma309');
var sensor = new Sensor({pin:19});

sensor.on('alert', (duration) => {
    console.log('Sound detected', duration);
});

````
