# mini_project
Gas leakage, Fire and Smoke Detection System with Alarm and SMS Alert
# Components Used

- Arduino UNO
- MQ2 Gas Sensor
- Flame Sensor
- Buzzer
- GSM Module (SIM900A)
- SIM Card
- umper Wires
- Power Supply (5V)

## Features

- Detects gas, fire, and smoke
- Sounds a buzzer when danger is detected
- Sends SMS alert to user

## How It Works

1. Sensors detect gas/smoke/flame.
2. If levels cross a safe limit:
   - Buzzer turns on
   - SMS is sent via GSM module

---

## Usage

1. Connect the circuit as per diagram.
2. Upload the code using Arduino IDE.
3. Insert SIM into GSM module.
4. Power the setup.
5. Test with lighter or smoke to trigger alerts.

---

## Output

- Buzzer beeps
- SMS alert:  
  `"Alert! Gas/Fire/Smoke detected at location."`

---

