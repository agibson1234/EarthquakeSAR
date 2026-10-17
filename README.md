# EarthquakeSAR — Team 4

## Project Overview

EarthquakeSAR is an Unreal Engine 5.8 simulation environment developed to represent the aftermath of a major earthquake in an urban and residential setting.

The environment is intended to support future search-and-rescue operations involving unmanned aerial vehicles (UAVs) and ground robots.

## Environment Structure

The environment is organized around a residential neighborhood containing:

- Four residential buildings
- Intersecting roads and an urban street network
- Open areas for potential rescue operations
- Space for damaged structures, rubble, and obstacles

The primary map is located within the Unreal Engine project's `Content` directory.

## Assets Used

The project incorporates assets from the Fab marketplace and Unreal Engine's built-in tools.

Known asset sources include:

- **Modular Urban Houses** — residential architecture
- **Unfinished Building** — structural building elements and industrial environment assets
- **Unreal Engine primitives and materials** — environmental layout and supporting geometry

Additional assets included in the final map should be documented with their creator names and Fab listing URLs.

## Earthquake and Disaster Features

The scenario is designed to illustrate several consequences of a major earthquake, including potential structural collapse, debris accumulation, road obstructions, and damage to the built environment.

## Navigation Considerations

**Ground robots:** Roads and open areas are intended to provide accessible routes for future ground-based search-and-rescue robots. Rubble and structural obstacles can create areas that require rerouting.

**UAVs:** Aerial robots could inspect collapsed structures, rooftops, and locations that are inaccessible or difficult to reach from the ground.

Survivor locations and autonomous navigation capabilities can be incorporated in future development.

## Running the Project

1. Install Unreal Engine 5.8.
2. Clone the GitHub repository.
3. Obtain any Fab assets that must be downloaded separately, according to their licenses.
4. Open `EarthquakeSAR.uproject`.
5. Open the completed earthquake level from the Content Browser.
6. Allow Unreal Engine to load the environment and compile shaders if required.

## Known Issues and Future Work

- Some imported assets may have significant performance requirements.
- There are limited free assets to implement via FAB.

- The environment has not yet been integrated with autonomous UAV or ground-robot controllers.
- Additional collision and navigation testing may be required.
- Further enhancements could include dynamic structural destruction, dust effects, aftershocks, and survivor detection.

## Project Information

- **Team:** Team 4
- **Engine:** Unreal Engine 5.8
- **Project:** Earthquake Post-Disaster Environment
- **Purpose:** Search-and-rescue simulation and robotic navigation research

## Project Screenshots




<img width="695" height="523" alt="Screenshot 2026-10-16 at 11 25 45 PM" src="https://github.com/user-attachments/assets/63f8882a-51f9-4479-a46c-57afd8157373" />
<img width="638" height="593" alt="Screenshot 2026-10-16 at 11 25 04 PM" src="https://github.com/user-attachments/assets/46b3a4fc-04e7-4e69-b3e3-53fa18bc480c" />
<img width="1014" height="581" alt="Screenshot 2026-10-16 at 11 24 11 PM" src="https://github.com/user-attachments/assets/31bba667-4b10-482b-8d03-a5a6d144cbb4" />

