
# Svelvik CO₂ Seismic Monitoring – MW3 Zone Analysis

This project analyzes SEG-2 seismic data from the Svelvik CO₂ Field Lab to investigate time-lapse changes in the subsurface caused by CO₂ plume migration. The focus is on a receiver zone near Monitoring Well 3 (receiver indices 40–70), where seismic responses to CO₂ injection are expected to be most visible.

## 📌 Objective
To detect and interpret plume-related changes in:
- Waveform shape and amplitude
- Signal energy (envelope)
- First arrival time (velocity shift)

## ✅ Key Findings (MW3 Region)
### 🔹 Amplitude Comparison
Post-injection waveforms exhibited significant attenuation compared to baseline, indicating energy loss due to plume interaction.

### 🔹 Envelope Analysis
- Baseline traces showed strong, focused energy.
- Post-injection traces revealed dampened, flattened envelopes.
- Some traces nearly lost signal entirely → suggests saturation.

### 🔹 Arrival Time Shift
- Mean delay (Post vs Baseline): **0.000093 s**
- Indicates slight velocity drop due to CO₂ presence in pore space.

## 🧠 Interpretation
> These results confirm local plume effects in the MW3 region, characterized by energy scattering, partial saturation, and minor velocity reduction. The combination of envelope decay and arrival time shift strongly supports CO₂ plume migration into the monitoring zone.

## 🛠️ Tools Used
- Python 3 with ObsPy
- SEG-2 seismic files (baseline, injection, post-injection)
- Custom waveform and envelope comparison scripts

## 📂 Workflow
```
Files → Inspect → Clean → Compare (Baseline vs Injection) → Interpret (MW3)
```

---

**This project demonstrates the value of focused receiver analysis in shallow CO₂ injection scenarios and supports broader MMV practices in CCS.**
