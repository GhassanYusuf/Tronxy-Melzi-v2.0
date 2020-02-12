# Tronxy-Melzi-v2.0
Add A Probe And Enable Auto Leveling With Marlin Firmware 1.1.9

```
#define X_STEP_PIN          15
#define X_DIR_PIN           21
#define X_MIN_PIN           18

#define Y_STEP_PIN          22
#define Y_DIR_PIN           23
#define Y_MIN_PIN           19

#define Z_STEP_PIN          3
#define Z_DIR_PIN           2
#define Z_MIN_PIN           20

#define E0_STEP_PIN         1
#define E0_DIR_PIN          0

#define LED_PIN             27

#define FAN_PIN             4 

#define HEATER_0_PIN        13  // extruder

#define HEATER_BED_PIN      10  // bed (change to 12 for breakout pin on header)
#define X_ENABLE_PIN        14
#define Y_ENABLE_PIN        14
#define Z_ENABLE_PIN        26
#define E0_ENABLE_PIN       14

#define TEMP_0_PIN          7   // Analogue pin
#define TEMP_BED_PIN        6   // Analogue pin
#define SDSS                31

#define SLAVE_CLOCK         16
```

### Refferances
[Developer Of Melzi](https://github.com/reprappro/melzi) 

[RepRap WiKi - Melzi](https://reprap.org/wiki/Melzi)

[Geeetech WiKi - Melzi](http://www.geeetech.com/wiki/index.php/Melzi_V2.0)

[Wiring Bl Touch - Melzi](https://www.antclabs.com/wiring3)