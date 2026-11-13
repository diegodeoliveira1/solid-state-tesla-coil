# Testing, results, and limitations

## Test observations

| Recording | What is observable | What is **not** established |
|---|---|---|
| [Successful operation](../assets/videos/successful-test.mp4) (approximately 14.7 s) | A visible purple discharge from the Tesla coil during the recording | Exact output voltage, frequency, current, arc power, long-term reliability, or safety |
| [MOSFET failure-related recording](../assets/videos/mosfet-failure-test.mp4) (approximately 4.2 s) | Brief visible discharge and the end of that test; the team reported MOSFET failure | The precise electrical/thermal cause of the failure |

The two recordings represent **separate tests**. The successful-operation video is not a continuation of the failure recording, and no repair history is claimed.

## Assessment against project objectives

| Objective | Outcome |
|---|---|
| Assemble an approximately one-foot-tall solid-state Tesla coil | **Achieved** — the physical device was constructed and photographed |
| Implement switching with a power MOSFET and supporting passive/protection components | **Implemented in the prototype** per the team's documentation |
| Produce a visible high-voltage discharge | **Achieved** — visible in the recorded tests |
| Achieve sustained reliable operation with characterized electrical limits | **Not established**; one test ended in reported MOSFET failure and no quantitative characterization data were supplied |

## Reported MOSFET failure: hypotheses, not conclusions

1. **Drain voltage transients.** Switching an inductive load can generate brief overvoltage events that exceed component limits.
2. **Current and thermal stress.** High current or inadequate heat removal can exceed device safe operating limits.
3. **Gate/feedback behavior.** Unintended timing or gate disturbances can raise switching losses.
4. **Connection integrity.** Loose or inconsistent soldered connections may alter circuit behavior.

No gate waveform, drain-source waveform, device-temperature trace, or controlled component-failure analysis was recorded here. Therefore, a definitive failure root cause would be speculation.

## Engineering lessons

- A functional output is not the same as a validated, reliable system.
- Electrical component selection, protection strategies, construction quality, and testing all affect performance.
- Clear experiment records should separate **observations** from **interpretations**.

## Next steps for a future, supervised redesign

The first priority is an independent **electrical-safety review by qualified laboratory personnel**, not additional live demonstrations. Only with appropriate protective design and approved lab procedures would further work consider measured MOSFET switching waveforms, resonant behavior, thermal characteristics, and repeatability. No unverified measurements or certifications are asserted in this repository.
