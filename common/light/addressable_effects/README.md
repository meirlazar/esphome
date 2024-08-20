# ESPhome LED Effects Selection
Effects Selection for ESPhome addressable Lights like WS2812 with lambdas


## Including effect in configuration
```
light:
  - platform: [some addressable LED]
    ...
    effects:
      - !include esphome_led_effects/effects/[fxname].yaml
```


