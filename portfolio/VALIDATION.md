# Smart Hospital Bed: validation

## Current evidence

This documentation update inspected available text and file inventories. It did not execute the project, simulate a model or test hardware. Existing recorded results must be cited with their original conditions.

## Proposed checks

These are test plans. No row below is marked as passed.

| Check | Action | Evidence to retain | Status |
| :-- | :-- | :-- | :-- |
| V01: Heart-rate and EMG sensors | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V02: Environmental and motion sensors | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V03: Embedded acquisition | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V04: Servo positioning | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V05: Node-RED display | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |

## Project-specific checks

- Verify or recover: Sensor part numbers.
- Verify or recover: Pin map and wiring.
- Verify or recover: Firmware and Node-RED flows.
- Verify or recover: Calibration and bench results.

## Reporting rule

Report units, sample size, configuration, error bounds and failures. Separate a simulation result from a hardware result. Separate an emulator check from a physical-device check. A screenshot alone does not establish numerical accuracy.
