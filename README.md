# mrpattanapong.github.io
Public as Project of ENG55 1209 ARTIFICIAL INTELLIGENCE FOR ENGINEERS

## Functional 
### Map-Based Dashboard
Provides a geographical overview of the charging infrastructure with real-time status updates.
* **Interactive Map Integration** as Leaflet
* **Station Markers** – Render EV Charging Stations as dynamic pins based on GPS coordinates.
* **Quick View Tooltip/Sidebar** – Trigger a pop-up or sidebar on **Hover/Click** to display:
    * Station Name/ID
    * Current Status (Available, Charging, Offline, Fault)
    * Real-time Power Load (kW)
    * Electrical Metrics (Voltage and Current)

---

### Power Quality Monitoring (PQM)
Advanced analytics dashboard visualizing power quality data (simulated/mock data) across 7 key metrics:
* **Transients** – Display waveform graphs and event logs for sudden voltage surges.
* **Short Duration Variations** – Track occurrences of Voltage Dips/Sags, Swells, and Short Interruptions.
* **Long Duration Variations** – Monitor sustained Overvoltage, Undervoltage, and Long Interruptions.
* **Voltage Unbalance** – Calculate and visualize the percentage unbalance in 3-phase systems.
* **Harmonics** – Render Spectrum Bar Charts for harmonic orders, including **%THDv** and **%THDi**.
* **Voltage Fluctuation** – Provide trend graphs showing voltage flicker and oscillations over time.
* **Power Frequency Variation** – Plot system frequency (Hz) deviations against a time-series axis.

---

### Power Output Control
Administrative interface for managing power distribution and load balancing.
* **Current Limit Slider** – UI component to manually throttle or limit the Maximum Current for specific stations/connectors.
* **Defined Range** – Slider input constrained to 0% – 100% of the rated capacity.
* **Control Confirmation** – Inclusion of **Confirm** and **Cancel** actions to prevent accidental adjustments.
* **API Synchronization** – Dispatch an API request to the backend upon confirmation; update UI state only after receiving a "Success" response.

---
**Maintainer:** [mrpattanapong](https://github.com/mrpattanapong)
