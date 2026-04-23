# Project name: L-WAND-B/L-RBBT-B/L-BLLT-B/L-PLUG-B/SDIL/HDIL/CRNG/SCRNG/ROSE/NMDIL/LIPSTICK
## FW release note

Version: 1.0.0.3
Date: 2025/04/22
- Issue fix:
  - led sequence-'stand by' won't display after disconnect with device
  - led pattern toggle delay
  - motor sometime will stuck
- Modified:
  - led pattern5(only project: SDIL/NMDIL/LIPSTICK)
  - ROSE all led pattern
  - enhance travel lock detect function
  - low battery voltage(3.6V -> 3.25V)
  - NMDIL toggle led level button
  - 1 wire uart cmd
- Add:
  - save mode function(single tap pwr button can trigger save mode with app)
  - gatt cmd(can check with file: health-gatt-cmd-list-20260415)

---
Version: 1.0.0.2
Date: 2025/03/16
- Issue fix:
  - charging and charging full detect
  - OTA fail(with BLE app)
  - led stuck
- Modified:
  - button function(single button/double button)
  - led pattern
  - motor pattern
  - disable EDR(chip size limit)
  - disable log(chip size limit)
  - shutdown voltage(2.4V -> 3.0V)
- Add:
  - new project: NMDIL/SCRNG/LIPSTICK
  - support led ch2 & ch3
  - support motor ch2
  - travel lock/unlock
  - one-wire uart
  - can choose led is GRB or RGB
  - gatt cmd list

---
Version: 1.0.0.0
Date: 2025/12/30
- Issue fix:
- Modified:
- Add:
  - button pin define
  - led pin define
  - motor pin define
  - led pattern
  - motor pattern
  - motor level
  - charging led
