# To-Do
- [ ] IR Remote: Use INT3 on pin P5.5 for signal input. Implement Low Power mode to save battery.

- [ ] I2C Expansion: Add TXD register access with auto-clearing/sending logic.

- [ ] PWM Fix: Update source files to support a wider range of frequencies.

- [x] New Delay Function: Created a delay system that doesn't use standard timers.
    > Solution: Used PCA Software Timer.

    >Limit: PCA counter is shared; changing CH/CL may affect other PCA modules.

- [x] IR Modulation: Fixed modulation for CCP1 Port in uVision.

    > Solution: Manipulated CR (PCA Counter) directly instead of CCAPM1.

    >Limit: Affects all PCA modules due to shared counter.
