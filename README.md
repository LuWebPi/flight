# Ultimate Flight Simulator V11 — Sky Fortress Edition

A browser-based 3D flight simulator built with Three.js (r128). Single self-contained `index.html` file — just open it in any modern browser. No build step, no dependencies, no server needed.

## Features

### Aircraft (5)
- **Cessna 172** — light trainer, easy to fly, great for sightseeing
- **Airbus A320neo** — commercial jet with sharklets
- **Boeing 767** — heavy wide-body
- **F-22 Raptor** — fighter jet with missiles & flares, afterburner
- **Concorde** — supersonic delta-wing with 4 engines & afterburner

### Weather System
- **Clear** — sunny VFR
- **Rain** — reduced visibility, wet conditions
- **Snow** — snowfall particles
- **Storm** — heavy rain, turbulence, lightning + thunder

### World
- Procedural city (downtown skyscrapers, industrial, residential)
- Two airports with runways, taxiways, terminals, jet bridges, hangars, towers, runway lights
- River with bridges
- Lakes
- Mountains with snow caps
- Volumetric fly-through clouds
- Birds, AI traffic planes, ground traffic
- Day/Night cycle with sun, moon and stars

### Flight Model
- Realistic physics: thrust, drag, lift, gravity, stall, G-forces
- **Flaps** (multiple positions) — increase lift & drag
- **Spoilers / airbrake**
- **Wheel brakes**
- **Reverse thrust** (where applicable)
- **Autopilot**: Altitude Hold + Heading Hold
- Ground rolling physics, takeoff rotation, landing detection
- Overspeed structural failure, G-load structural failure
- Touchdown smoke & landing success toast

### HUD
- PFD (Primary Flight Display) artificial horizon
- Minimap with airports & heading
- Heading compass strip
- Speed & altitude tapes
- Telemetry: thrust, speed, alt, V/S, heading, G-force, flap position
- Stall / Pull-Up / Overspeed warnings
- Live score panel (flight time, distance, max speed, max altitude, landings)

### Cameras (4 modes)
- Chase, Cockpit, Orbit, Cinematic

### Audio
- Procedural engine, wind, explosion, missile, flare, landing chime, thunder sounds (Web Audio API)

### Controls
- **Touch / Mouse**: joystick, throttle slider, on-screen buttons
- **Keyboard (desktop)**:
  - `W/S` pitch · `A/D` roll · `Q/E` rudder
  - `Shift/Ctrl` throttle up/down
  - `B` brakes · `F` flaps · `V` spoilers · `L` gear
  - `C` camera · `N` day/night · `T` weather · `P` autopilot
  - `Space` missile · `X` flares · `R` restart

## How to run
Open `index.html` directly in a browser, or serve the folder with any static server:
```bash
python3 -m http.server 8000
```

Built on V10, massively extended in V11.
