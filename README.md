# Similar Product Template

This engine uses a Similar Product template identical to the one in the tapster demo. Instead, of view events it is modified to use like events.

Please refer to tapster tutorial: https://docs.prediction.io/demo/tapster/
Please refer to Similar Product Engine: https://docs.prediction.io/templates/similarproduct/quickstart/

## Requirements
Predictionio 0.9.2

## Instructions
change appName in engine.json to the name of your app in predictionIO.
Make sure you send data to the eventserver containing item data, user data, and like events.

start predictionio: pio-start-all
build the engine: pio build --verbose
train the engine: pio train
deploy the engine: pio deploy

