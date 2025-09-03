# Embedded-Electrical-Engineer
Tyler Wong's Application for Embedded Electrical Engineer at WindBorne Systems

Dear WindBorne Team,

What excites me most about engineering is the moment when something goes from a messy idea on a whiteboard to functioning in front of your eyes. I still remember soldering down the final components of a two-layer motor-control board I designed and watching the wheels of my autonomous vehicle spin to life for the very first time. That project started as a simple class requirement, but it became a crash course in problem solving. The result wasn’t just a working vehicle; it was proof that I could turn “what if” concepts into reliable solutions with meaningful performance.

I think that’s why the Embedded Electrical Engineer role at WindBorne speaks to me. Your team’s focus on rapidly iterating between design, bring-up, and validation mirrors how I naturally work. Whether it’s routing elegant power paths on a PCB or investigating a bug that hides in plain sight, I find energy in moving applying theory into practice.

Beyond the technical side, I care about the impact of the systems I help build. At UC Davis, I led projects that not only met technical goals but also engaged broader communities — from embedded IoT devices that translated languages in real time to interactive systems that brought 28,000+ new attendees to our campus event. For me, hardware is more than components, it’s about unlocking new experiences and possibilities.

I’d be thrilled to bring this blend of creativity, persistence, and systems thinking to WindBorne, helping your team push forward the next generation of flight hardware. Thank you for your time and consideration, I’d love the chance to contribute to your mission.

Best regards,
Tyler Wong

# PCB Highlight
One creative feature of this PCB is how I routed both the servo PWM signals and the DC motor driver lines in a way that cleanly separates the high-current power path (highlighted in red) from the low-noise control traces.

Instead of using a bulky shunt resistor, I took advantage of the ground return path placement and carefully positioned the current sense trace right at the motor driver’s output stage, which gave me accurate readings without needing extra board space. It’s a small but elegant trick — the kind of detail that reduces BOM cost while keeping the design compact and robust.

You could call it a “cute way” of sneaking in current sensing and power/logic isolation, while still making the layout beginner-friendly for assembly and debugging.

