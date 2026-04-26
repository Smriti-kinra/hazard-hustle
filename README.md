**Pipeline Hazard Simulator — Hazard Hustle**

Overview

Hazard Hustle is a web-based applet that simulates CPU pipeline execution and visualizes RAW (Read After Write) hazards. It enables users to observe instruction flow across pipeline stages and understand hazard detection and resolution using stalling and data forwarding.

⸻

Features

* Interactive instruction configuration (ADD, SUB, LW, SW)
* Pipeline visualization (cycle vs instruction table)
* Hazard detection and classification
* Configurable pipeline:
    * 5-stage and 4-stage pipelines
    * Data forwarding (ON/OFF)
    * Split-phase register access (ON/OFF)
* Step-by-step and automatic simulation
* Hazard analysis and explanation panel

⸻

Assumptions

* Only RAW hazards are considered
* No structural or control hazards
* In-order execution
* Hazard detection at decode stage
* Stall insertion based on dependency and configuration

(Consistent with the report design and assumptions  )

⸻

How to Run

Open the following file in any modern web browser:
index.html

Or access via GitHub Pages.


Author

* Kavyaa Agrawal
* Smriti Kinra
* Avani Mahawar

⸻

License

Academic use only.
