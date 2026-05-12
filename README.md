# mrpattanapong.github.io
Public as Project of ENG55 1209 ARTIFICIAL INTELLIGENCE FOR ENGINEERS

## 3. Functional Requirements (FR)

### 3.1 Map-Based Dashboard
Provides a geographical overview of the charging infrastructure with real-time status updates.
* **FR-1.1: Interactive Map Integration** – Embed an interactive map (Google Maps or OpenStreetMap) for spatial visualization.
* **FR-1.2: Station Markers** – Render EV Charging Stations as dynamic pins based on GPS coordinates.
* **FR-1.3: Quick View Tooltip/Sidebar** – Trigger a pop-up or sidebar on **Hover/Click** to display:
    * Station Name/ID
    * Current Status (Available, Charging, Offline, Fault)
    * Real-time Power Load (kW)
    * Electrical Metrics (Voltage and Current)

---

### 3.2 Power Quality Monitoring (PQM)
Advanced analytics dashboard visualizing power quality data (simulated/mock data) across 7 key metrics:
* **FR-2.1 Transients** – Display waveform graphs and event logs for sudden voltage surges.
* **FR-2.2 Short Duration Variations** – Track occurrences of Voltage Dips/Sags, Swells, and Short Interruptions.
* **FR-2.3 Long Duration Variations** – Monitor sustained Overvoltage, Undervoltage, and Long Interruptions.
* **FR-2.4 Voltage Unbalance** – Calculate and visualize the percentage unbalance in 3-phase systems.
* **FR-2.5 Harmonics** – Render Spectrum Bar Charts for harmonic orders, including **%THDv** and **%THDi**.
* **FR-2.6 Voltage Fluctuation** – Provide trend graphs showing voltage flicker and oscillations over time.
* **FR-2.7 Power Frequency Variation** – Plot system frequency (Hz) deviations against a time-series axis.

---

### 3.3 Power Output Control
Administrative interface for managing power distribution and load balancing.
* **FR-3.1: Current Limit Slider** – UI component to manually throttle or limit the Maximum Current for specific stations/connectors.
* **FR-3.2: Defined Range** – Slider input constrained to 0% – 100% of the rated capacity.
* **FR-3.3: Control Confirmation** – Inclusion of **Confirm** and **Cancel** actions to prevent accidental adjustments.
* **FR-3.4: API Synchronization** – Dispatch an API request to the backend upon confirmation; update UI state only after receiving a "Success" response.

---
**Project:** ENG55 1209 ARTIFICIAL INTELLIGENCE FOR ENGINEERS  
**Maintainer:** [mrpattanapong](https://github.com/mrpattanapong)
