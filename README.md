# MultiWii + Sonar v2

**Improved MultiWii firmware with enhanced sonar altitude hold (2014)**

> Iteration on the original sonar integration -- better filtering, more stable hover.

---

## What Is This?

The second iteration of the MultiWii sonar modification. After testing the first version in real flight conditions, this version includes **improved sonar signal filtering and altitude hold stability**.

## Improvements Over v1

- Better noise filtering on sonar readings
- More stable altitude PID tuning
- Reduced oscillation during hover
- Improved handling of out-of-range readings

## Technical Details

- **MultiWii 2.4** base firmware
- **Ultrasonic sonar** for altitude measurement
- **QUADX** frame configuration
- Optimized for indoor laboratory flight experiments

## Key Files

- `MultiWii/MultiWii.ino` -- Main firmware
- `MultiWii/config.h` -- Configuration and tuning parameters
- `MultiWii/Sensors.cpp` -- Improved sonar processing

## Related Projects

- [multiwii-sonar](https://github.com/daletoniris/multiwii-sonar) -- Original sonar version
- [multiwii-humidity-sensor](https://github.com/daletoniris/multiwii-humidity-sensor) -- Environmental sensor variant
- [drone-pilot](https://github.com/daletoniris/drone-pilot) -- Companion computer autopilot
- [fly-drone-controller](https://github.com/daletoniris/fly-drone-controller) -- Python drone control tools

## License

GPL v3

---

*Daniel Dieser -- Puerto Madryn, Patagonia, Argentina*
*Telegram: [@mrmoz33](https://t.me/mrmoz33)*
