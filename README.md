# Embedded-Electrical-Engineer
Tyler Wong's Application for Embedded Electrical Engineer at WindBorne Systems

One creative feature of this PCB is how I routed both the servo PWM signals and the DC motor driver lines in a way that cleanly separates the high-current power path (highlighted in red) from the low-noise control traces.

Instead of using a bulky shunt resistor, I took advantage of the ground return path placement and carefully positioned the current sense trace right at the motor driver’s output stage, which gave me accurate readings without needing extra board space. It’s a small but elegant trick — the kind of detail that reduces BOM cost while keeping the design compact and robust.

You could call it a “cute way” of sneaking in current sensing and power/logic isolation, while still making the layout beginner-friendly for assembly and debugging.
