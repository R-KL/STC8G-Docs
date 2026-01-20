# Logs
Related to Microcontroller
> Note: These logs track the STC8G1K17A peripheral implementation.

## 📅 16 / 02 / 2025
- **Peripheral Setup:** Recovered PWM and ADC configurations.

- **Refactoring:** Created separate Header and Source files for ADC and PWM modules to improve project modularity.

## 📅 22 / 02 / 2025
- **PWM Tuning:** Fixed custom frequency logic.

- **Current Status:** Reliable between 0-250 Hz. Performance above this range is currently unstable.

- **Servo Control:** Successfully controlled a servo motor, though fine-tuning is required.

- **Timing Insight:** Discovered frequency variation is best handled via Timer0 Overflow.
- **Temporary Solution:** Initialize Timer0 after PWM Initialization with the required TimePeriod.

- **Formula:** 
    ```c
    Timer0 timePeriod = 1 / (PWM_freq * 256)
    ```
    > Note: PWM is set to work with Timer0 Overflow pulses.

## 📅 12 / 03 / 2025
- **UART Library:** Completed Header and Source files.

- **Default:** 9600 Baud @ 11.0592MHz.

- **PC Link:** Successfully sent and received data between the MCU and PC using the STC Programmer UART helper.

- **Timer Conflict:** 
    > ⚠️ Warning: UART uses Timer1 and PWM uses Timer0. Using both simultaneously leaves no hardware timers remaining.

## 📅 23 / 03 / 2025
- **I2C Prototype:** Slave mode tested on STC8G1K8 using the STC8G1K17A library.    
- **Issues:** Partially successful; encountering blank data packets. Suspect I2C Interrupt timing.

## 📅 14 / 04 / 2025
- **PCA Modes:** Tested Software mode and High Speed Pulse Output Mode (HSOM).

- **HSOM Logic:** Since the counter toggles at a fixed `pca_clk / 2^16`, I implemented a workaround using interrupts to reset CH and CL registers to `(2^16 - ticks)` to control frequency.

- **IR Protocol:** Implemented NEC format timing.

- **Current Issue:** Signal is accurate but not yet modulated (likely a main loop timing conflict).

## 📅 13 / 07 / 2025
- **I2C Improvements:** Added pin-switching functionality.

- **Buffer Access:** Streamlined RXD buffer access.

    >Note: The first byte is currently ignored; using #value as a placeholder.