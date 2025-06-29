# Svelvik CO₂ Seismic Monitoring

This project analyzes SEG-2 seismic data from the Svelvik CO₂ Field Lab to investigate seismic changes in the subsurface caused by CO₂ plume migration.

Using Python-based workflows, we inspect, clean, and compare seismic responses from:
- **Baseline data** (before injection)
- **Injection data**
- **Post-injection data**

---

## 🎯 Objective

To detect and interpret CO₂-related changes in:
- Waveform shape and amplitude
- Signal energy (envelope)
- First arrival time (velocity shift)

---

## 🔍 Key Findings

### Amplitude Envelope
Post-injection waveforms show reduced amplitude envelopes compared to baseline, indicating energy loss due to plume-induced scattering and attenuation.

### Arrival Time Shift
First arrivals occur earlier after injection, suggesting increased velocity in the plume zone (likely due to CO₂ saturation effects).

### Multi-Trace Overlay
Differences in waveform shape and phase are observed across receivers, revealing plume-related changes.

---

## 🧰 Tools Used

- **Python 3** with [ObsPy](https://github.com/obspy/obspy)
- **SEG-2 files**: Baseline, injection, and post-injection data
- **Matplotlib** for visual comparisons and envelope overlays

---

## 🔁 Workflow

`Files → Inspect → Clean → Compare (Baseline vs Injection) → Interpret`

---

## 📌 Summary

This project confirms seismic evidence of CO₂ plume migration through cross-phase comparisons and waveform analysis. It provides a practical example of CO₂ monitoring in shallow injection experiments and lays the groundwork for future MMV applications in CCS.
