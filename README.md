# PRAAN Prototype Explorer

Interactive 3D viewer for the PRAAN Rev C breath-analyzer mechanical prototype.

## Open the viewer

Download this repository as a ZIP, extract it, and open `index.html` in a browser with WebGL support. The viewer is self-contained and does not need a server, installation, or external asset downloads.

## Controls

- Rotate and zoom the model; switch between assembled, internal, exploded and PCB views.
- In **Exploded**, enable **Show Labelings** to identify parts. Use the searchable key for explanations, including small fasteners.
- Select, hide or isolate parts; show optional reserved spaces and section cuts.
- Review dimensions, measure between displayed surfaces, and export a PNG or parts-key CSV.

The inventory contains 118 modeled parts and placements, plus four optional reserved spaces. The body is 180 mm high × 80 mm wide × 60 mm deep. Its 2.8-inch display has a 43.2 × 57.6 mm active area.

## Files

- `index.html` — complete viewer, embedded geometry, materials, application code and third-party library notices.
- `Parts_key.csv` — numbered part inventory and explanations.

## Prototype status

This is a mechanical fit and component-placement model. The custom PCB is unrouted. Purchased-component fit, thermal performance and assay performance still need physical validation. Visual materials and markings do not establish circuit connections or sensing results.

Supplier ESP32 and LCD geometry is attributed in the embedded model. Manufacturer assets remain subject to their owners' rights; this repository does not assert an open license for those assets. Existing Three.js and Svelte notices remain embedded in the viewer.

This repository upload does not configure a website deployment.
