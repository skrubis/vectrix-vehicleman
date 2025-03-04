
# vectrix-vehicleman
Vectrix VX1 BMS manager + TC charger control + LTE connectivity + GPS tracker + Alarm + whatever else time can solve.

meant to be used together with Openinverter Flying ADC BMS

Includes:

 - ESP32 + SD card
  - Battery backup with charger for esp + LTE (1x18650)
   - Footprint for GigaVESC HV (150-180V?)@2~3A(?) -> 12V [DCDC](https://github.com/kaminaris/GigaESC/tree/master/PowerBoard/TL494V2OC)
   - LTE modem (SIM7070G with GNSS) + 1 SIM
   - 1x CAN TWAI transceiver
   - 2x CAN SPI transceiver (in case TC charger(s) are on the same address or say multiple R4850G2 are used)
   - A few relays and mosfets for external loads
   - Accelerometer/IMU for "alarm" functionality
   - Moisture/temp sensor for condensation detection (?)
   - RTC
   - Accelerometer or Gyro with INT for "alarm" wakeup
   -TYPE 2 charging CP PP control
   - External antenna PCB for active GNSS + passive LTE should be here as well.

NOT TESTED, NOT VERIFIED!
CC-BY-NC 4.0

