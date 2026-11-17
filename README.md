# Wireless Power Transfer

Coil designs for inductive and resonant wireless power transfer (Qi ~200 kHz, AirFuel 6.78 MHz and 13.56 MHz ISM), simulated in ANSYS HFSS, plus photos of fabricated prototypes. Each model folder has a structure image, a README with full specifications, and the original HFSS project file so you can download it and re-run the simulation.

| Model | Type | Frequency (band) | Year |
|---|---|---|---|
| [Planar spiral wire coils](Planar-Spiral-Wire-Coils/) | Wire coil pairs, 3 designs | 1–35 MHz (HF) | 2017 |
| [Double-layer spiral resonator](Double-Layer-Spiral-Resonator-6.78MHz/) | PCB resonator + excitation loop | 6.78 MHz (ISM) | 2016 |
| [Dual-band coils 200 kHz / 6.78 MHz](Dual-Band-Coils-200kHz-6.78MHz/) | Qi + AirFuel PCB coils | 0.2 / 6.78 MHz | 2018 |
| [Dual-band coils 6.78 / 13.56 MHz](Dual-Band-Coils-6.78-13.56MHz/) | Dual HF ISM PCB coils | 6.78 / 13.56 MHz | 2018 |
| [Spiral coils for MR-WPT, ~1 MHz](Spiral-Coils-MR-WPT-1MHz/) | 4-coil magnetic-resonance link, spiral resonators | 0.5–1.5 MHz (MF) | 2018 |
| [Fabricated prototypes](Fabricated-Prototypes/) | Photos of built coils and test setup | – | – |

## Gallery

<table>
<tr><td align="center"><a href="Planar-Spiral-Wire-Coils/"><img src="Planar-Spiral-Wire-Coils/coils_3d.png" width="240" alt="Planar spiral wire coils"></a><br><sub><a href="Planar-Spiral-Wire-Coils/">Planar spiral wire coils</a></sub></td><td align="center"><a href="Double-Layer-Spiral-Resonator-6.78MHz/"><img src="Double-Layer-Spiral-Resonator-6.78MHz/coil_top_view.png" width="240" alt="Double-layer spiral resonator"></a><br><sub><a href="Double-Layer-Spiral-Resonator-6.78MHz/">Double-layer spiral resonator</a></sub></td><td align="center"><a href="Dual-Band-Coils-200kHz-6.78MHz/"><img src="Dual-Band-Coils-200kHz-6.78MHz/coils_layout.png" width="240" alt="Dual-band coils 200 kHz / 6.78 MHz"></a><br><sub><a href="Dual-Band-Coils-200kHz-6.78MHz/">Dual-band coils 200 kHz / 6.78 MHz</a></sub></td></tr>
<tr><td align="center"><a href="Dual-Band-Coils-6.78-13.56MHz/"><img src="Dual-Band-Coils-6.78-13.56MHz/coils_layout.png" width="240" alt="Dual-band coils 6.78 / 13.56 MHz"></a><br><sub><a href="Dual-Band-Coils-6.78-13.56MHz/">Dual-band coils 6.78 / 13.56 MHz</a></sub></td><td align="center"><a href="Spiral-Coils-MR-WPT-1MHz/"><img src="Spiral-Coils-MR-WPT-1MHz/coil_structure.png" width="240" alt="Spiral coils for MR-WPT, ~1 MHz"></a><br><sub><a href="Spiral-Coils-MR-WPT-1MHz/">Spiral coils for MR-WPT, ~1 MHz</a></sub></td><td align="center"><a href="Fabricated-Prototypes/"><img src="Fabricated-Prototypes/dual_layer_receiver_coil_mobile_charger.png" width="240" alt="Fabricated prototypes"></a><br><sub><a href="Fabricated-Prototypes/">Fabricated prototypes</a></sub></td></tr>
</table>

## Download and simulate

Open a project file (`.aedt` or `.hfss`) on GitHub and click **Download raw file**, or use **Code → Download ZIP** to get everything. Open it in ANSYS HFSS / Electronics Desktop. The geometry uses the ACIS kernel, so AEDT 2025 R1 and later cannot open these files directly: open and save them once in AEDT 2024 R2 or earlier. Results are not included; re-run the analysis setups to regenerate them.

## Folder structure

```
Wireless-Power-Transfer/
├── Planar-Spiral-Wire-Coils/
├── Double-Layer-Spiral-Resonator-6.78MHz/
├── Dual-Band-Coils-200kHz-6.78MHz/
├── Dual-Band-Coils-6.78-13.56MHz/
├── Spiral-Coils-MR-WPT-1MHz/
└── Fabricated-Prototypes/
```

See also: [RF-Antenna](https://github.com/fereshtianamir-lab/RF-Antenna) – antenna and transmission-line models in HFSS, CST and FEKO.
