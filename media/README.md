# media/ — what is in these folders

All files here are copied unmodified from `07_Experiment_Media/` of the private build archive. The
filenames are the archive's own (camera names, timestamps, screen-grab ids) so that every image can be
traced back to the lab notebook. Nothing was retouched, cropped, colour-corrected or re-plotted.

## photos/

| File | Resolution | What it shows |
| --- | --- | --- |
| `3605ee3b-e1d7-4276-ab2e-0b08db5e8eba.jpg` | 1920 × 2560 | Stage-1 breadboard prototype, top-down, with the dendrite, comparator, membrane and output stages all present |
| `1788672036713.png` | 1195 × 896 | The same prototype in its harness on an Analog Discovery Studio, flying leads to the pulse inputs |
| `PXL_20261008_234742183~2.jpg` | 4000 × 3000 | Stage-2 hand-milled two-layer board, fully populated |
| `PXL_20261008_222901567.MACRO_FOCUS.jpg` | 3000 × 4000 | Macro detail of one logic package and its local passives on the milled board |
| `PXL_20261024_012351358.jpg` | 3000 × 4000 | Stage-3 measurement configuration: neuron board on the instrument plus the probe/interface board |

## waveforms/

| File | Type | What it shows |
| --- | --- | --- |
| `adaptive_learning_transient_500ms.png` | **Simulation re-plot** of exported simulation samples (matplotlib figure, not a scope capture) | 500 ms transient: 12 learning pairs, HOLD at ~120 ms, then 38 detection pairs; inputs, control, `VCTRL`, `DEND90`, `SPIKE90`, extracted delay and per-pair spike count. Axes are model time and model volts |
| `final_measurement_early.png` | Raw scope screen capture (2026-10-24 20:41) | Four probe channels, 5 V/div, 100 ms/div, 8192 samples at 8 kHz — early assembly |
| `final_measurement_late.png` | Raw scope screen capture (2026-10-24 20:38) | Same settings and probe points — revised assembly, after polarity/offset re-set |

## What is deliberately absent

The archive also contains figures that embed full circuit diagrams — component designators, values,
supply rails, net names. Those are design documents, not results, and they are **not** published here
even though they live in the same folder. The same applies to the bare-copper routing photography:
a high-resolution photograph of a milled board is a layout image in all but name.

If you are reviewing this work and need the withheld material, contact the author through the
repository issues.
