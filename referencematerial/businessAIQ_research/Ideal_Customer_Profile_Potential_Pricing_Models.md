Below are **six detailed, itemized proposals**—two each (New Build and Renovation) for the three commercial clients we profiled for **Years 1–2**. Each table includes:

- **Product** with brand and model suggestions suitable for commercial use.  
- **Quantity** estimates appropriate to the client's scope.  
- **Unit Price (Retail)** based on typical street pricing in 2025.  
- **Estimated Labor Hours** at a standard rate of **\$125/hour** for commercial technician work.  
- **Totals** for hardware, labor, and project.

All systems will be **integrated** via an on-premise Home Assistant (HA) controller on a small business–grade mini PC or similar commodity hardware, providing advanced automation, local data control, and user-friendly dashboards. We assume each project includes **basic** or **moderate** building wiring tasks (Ethernet runs, sensor cabling) but does **not** account for major rewiring or electrical panel expansions (handled by other trades if required).

---

## 1) Paramount Dental Clinic (Pasadena, CA)

### A. **New Build Proposal**  
**Scenario**: Paramount Dental Clinic is constructing a **new** 3,500 sq ft dental facility from the ground up. We'll coordinate with their general contractor and architect to integrate smart lighting, HVAC, and security from day one. This allows more seamless cable routing, dedicated closet space for gear, and clean device mounting.

| **Item**                                                      | **Qty** | **Brand / Model**                    | **Unit Price** | **Est. Labor** <br>(hrs each) | **Labor Cost** <br>(\$125/hr) | **Hardware Subtotal** | **Labor Subtotal** | **Line Total** |
|---------------------------------------------------------------|--------:|--------------------------------------|---------------:|------------------------------:|------------------------------:|-----------------------:|--------------------:|---------------:|
| 1. **HA Controller** (mini PC) + UPS                         |       1 | Intel NUC + APC 600VA UPS            |    \$900       | 2 hrs                        | \$250                        | \$900                 | \$250              | \$1,150        |
| 2. **Smart Thermostats** (for 3 zones)                       |       3 | Ecobee SmartThermostat Pro           |    \$250       | 1 hr per thermostat          | \$125 ea * 3 → \$375         | \$750                 | \$375              | \$1,125        |
| 3. **Occupancy Sensors** (wireless, for exam rooms/hall)     |       8 | Lutron Vive Radio Powr Savr (Ceiling)|    \$100       | 0.5 hr each                  | \$62.50 ea * 8 → \$500        | \$800                 | \$500              | \$1,300        |
| 4. **Lighting Control Hubs** (for 2 zones)                   |       2 | Lutron Vive Hub (small commercial)   |    \$400       | 2 hrs each                   | \$250 ea * 2 → \$500         | \$800                 | \$500              | \$1,300        |
| 5. **LED Lighting Fixtures** <br>(Exam rooms + Reception)    |      20 | Commercial LED Panels (2x2, dimmable)|    \$80        | 0.5 hr each                  | \$62.50 ea * 20 → \$1,250     | \$1,600               | \$1,250            | \$2,850        |
| 6. **Access Control System** (main door)                     |       1 | Kisi Pro Controller + 2 Readers      |    \$1,000     | 4 hrs total                  | \$500                        | \$1,000               | \$500              | \$1,500        |
| 7. **Security Cameras** (lobby, hallway, exterior)           |       4 | Ubiquiti UniFi G4 Dome               |    \$180       | 1 hr each                    | \$125 ea * 4 → \$500         | \$720                 | \$500              | \$1,220        |
| 8. **PoE Network Switch** (8-port)                           |       1 | Ubiquiti UniFi Switch 8 (150W)       |    \$300       | 2 hrs                        | \$250                        | \$300                 | \$250              | \$550          |
| 9. **Installation Supplies** (cables, connectors, etc.)      |   n/a   | (Misc. Materials)                    |    \$400       | --                           | --                           | \$400                 | --                 | \$400          |
| 10. **Programming & Commissioning** (system-wide)            |   n/a   | (Setup automations, test, training)  |    --          | 10 hrs total                 | \$1,250                      | --                    | \$1,250            | \$1,250        |
| **Subtotal Hardware**                                        |         |                                      |               |                              |                               | **\$6,270**           |                    |               |
| **Subtotal Labor**                                           |         |                                      |               |                              |                               |                       | **\$5,175**        |               |
| **Total Estimated**                                          |         |                                      |               |                              |                               |                       |                    | **\$11,445**   |

**Scope & Features**:
- **HVAC**: Zoned climate control with **occupancy-based** adjustments.  
- **Lighting**: Automated exam-room lights that dim when unoccupied. Lobby scheduling for open hours.  
- **Access Control**: Single main door with RFID-based entry for staff. Expandable for future additional door readers.  
- **Security & Monitoring**: 4 cameras covering key areas, integrated into Home Assistant for event-based alerts.  
- **Proactive Integration**: Wires and devices planned during construction → minimal disruption, clean install.  

---

### B. **Renovation Proposal**  
**Scenario**: Paramount Dental Clinic is refreshing an **existing** 3,500 sq ft space with modest interior renovations (new flooring, updated reception). We'll coordinate with other trades but must work around some existing wiring and building constraints.

| **Item**                                                      | **Qty** | **Brand / Model**                    | **Unit Price** | **Est. Labor** <br>(hrs each) | **Labor Cost** <br>(\$125/hr) | **Hardware Subtotal** | **Labor Subtotal** | **Line Total** |
|---------------------------------------------------------------|--------:|--------------------------------------|---------------:|------------------------------:|------------------------------:|-----------------------:|--------------------:|---------------:|
| 1. **HA Controller** + UPS                                   |       1 | Intel NUC + APC 600VA                |    \$900       | 3 hrs (retrofit complexities) | \$375                        | \$900                 | \$375              | \$1,275        |
| 2. **Smart Thermostats** (2 existing zones)                   |       2 | Ecobee SmartThermostat Pro           |    \$250       | 1.5 hrs each                 | \$187.50 ea * 2 → \$375       | \$500                 | \$375              | \$875          |
| 3. **Occupancy Sensors** (wireless)                           |       6 | Lutron Vive Radio Powr Savr          |    \$100       | 1 hr each                    | \$125 ea * 6 → \$750         | \$600                 | \$750              | \$1,350        |
| 4. **Lighting Control Hub** (1 main area)                     |       1 | Lutron Vive Hub                      |    \$400       | 3 hrs                        | \$375                        | \$400                 | \$375              | \$775          |
| 5. **LED Retrofit Kits** (select exam rooms + reception)      |      12 | 2x2 LED Retrofit Panels, Dimmable    |    \$70        | 1 hr each                    | \$125 ea * 12 → \$1,500       | \$840                 | \$1,500            | \$2,340        |
| 6. **Access Control** (retrofit existing door)               |       1 | Kisi or HID upgrade kit              |    \$700       | 5 hrs (existing door wiring) | \$625                        | \$700                 | \$625              | \$1,325        |
| 7. **Security Cameras** (3 critical areas)                    |       3 | Ubiquiti UniFi G4 Dome               |    \$180       | 1.5 hrs each                 | \$187.50 ea * 3 → \$562.50    | \$540                 | \$562.50           | \$1,102.50     |
| 8. **Network Switch** (8-port PoE)                           |       1 | Ubiquiti UniFi Switch 8 (150W)       |    \$300       | 3 hrs (cable fishing)        | \$375                        | \$300                 | \$375              | \$675          |
| 9. **Installation Supplies** (cables, connectors)            |   n/a   | (Misc. Materials)                    |    \$300       | --                           | --                           | \$300                 | --                 | \$300          |
| 10. **Programming & Commissioning**                          |   n/a   | (Automation setup, testing)          |    --          | 8 hrs total                  | \$1,000                      | --                    | \$1,000            | \$1,000        |
| **Subtotal Hardware**                                        |         |                                      |               |                              |                               | **\$5,080**           |                    |               |
| **Subtotal Labor**                                           |         |                                      |               |                              |                               |                       | **\$5,637.50**     |               |
| **Total Estimated**                                          |         |                                      |               |                              |                               |                       |                    | **\$10,717.50**|

**Scope & Features**:
- **Lower lighting/HVAC scope** vs. new build (fewer zones).  
- Using existing door frames for access control → more labor for retrofitting cables.  
- Slightly fewer cameras and sensors due to existing layout constraints.  
- Occupancy sensors in main exam rooms/hallways to cut energy use.  
- Central dashboard (HA) for staff to monitor security camera feeds, adjust thermostats/lighting from reception.

---

## 2) Bloom & Branch Retail Boutique (Glendale, CA)

### A. **New Build Proposal**  
**Scenario**: Bloom & Branch is constructing a new 2,000 sq ft boutique store. They want a modern, tech-forward retail environment from day one.

| **Item**                                                 | **Qty** | **Brand / Model**                | **Unit Price** | **Est. Labor** <br>(hrs each) | **Labor Cost** <br>(\$125/hr) | **Hardware Subtotal** | **Labor Subtotal** | **Line Total** |
|----------------------------------------------------------|--------:|----------------------------------|---------------:|------------------------------:|------------------------------:|-----------------------:|--------------------:|---------------:|
| 1. **HA Controller** + UPS                              |       1 | Intel NUC + APC 600VA UPS        |    \$900       | 2 hrs                        | \$250                        | \$900                 | \$250              | \$1,150        |
| 2. **Smart Thermostat** (1 zone)                        |       1 | Ecobee SmartThermostat Pro       |    \$250       | 1 hr                         | \$125                        | \$250                 | \$125              | \$375          |
| 3. **Lighting Automation** (Motion + Scenes)            |       1 | Lutron Vive Starter Package      |    \$800       | 3 hrs                        | \$375                        | \$800                 | \$375              | \$1,175        |
| 4. **LED Track Lights** (accent areas)                  |      10 | Commercial Track LED Fixtures    |    \$60        | 0.5 hr each                  | \$62.50 ea * 10 → \$625       | \$600                 | \$625              | \$1,225        |
| 5. **Security Cameras** (front, stockroom, checkout)     |       3 | Ubiquiti UniFi G4 Bullet         |    \$160       | 1 hr each                    | \$125 ea * 3 → \$375         | \$480                 | \$375              | \$855          |
| 6. **Access Control** (rear employee door)              |       1 | Kisi Pro Controller + Reader     |    \$900       | 3 hrs                        | \$375                        | \$900                 | \$375              | \$1,275        |
| 7. **Music & Audio** (Ceiling speakers + Amp)           |       1 | Yamaha Commercial Sound Bundle   |    \$700       | 2 hrs                        | \$250                        | \$700                 | \$250              | \$950          |
| 8. **PoE Network Switch** (8-port)                      |       1 | Ubiquiti UniFi Switch 8 (150W)   |    \$300       | 2 hrs                        | \$250                        | \$300                 | \$250              | \$550          |
| 9. **Installation Supplies**                             |   n/a   | (Cabling, connectors)            |    \$200       | --                           | --                           | \$200                 | --                 | \$200          |
| 10. **Programming & Commissioning**                     |   n/a   | (Scenes, scheduling, training)   |    --          | 6 hrs total                  | \$750                        | --                    | \$750              | \$750          |
| **Subtotal Hardware**                                   |         |                                  |               |                              |                               | **\$5,130**           |                    |               |
| **Subtotal Labor**                                      |         |                                  |               |                              |                               |                       | **\$4,375**        |               |
| **Total Estimated**                                     |         |                                  |               |                              |                               |                       |                    | **\$9,505**    |

**Scope & Features**:
- **Lighting Scenes**: Morning, midday, and evening modes. Track lights for product highlights.  
- **Music Integration**: Background music with scheduling to match store hours.  
- **Security**: Cameras in strategic spots, integrated with motion triggers after hours.  
- **Access Control**: RFID or mobile credentials for staff only at the rear door.  
- **Central Dashboard**: Manager can quickly turn on/off all lights, music, AC from a tablet at checkout.

---

### B. **Renovation Proposal**  
**Scenario**: Bloom & Branch is refreshing a **current** store layout (2,000 sq ft). We'll integrate lighting, security cameras, and simple staff access control during a modest interior facelift.

| **Item**                                                 | **Qty** | **Brand / Model**            | **Unit Price** | **Est. Labor** <br>(hrs each) | **Labor Cost** <br>(\$125/hr) | **Hardware Subtotal** | **Labor Subtotal** | **Line Total** |
|----------------------------------------------------------|--------:|------------------------------|---------------:|------------------------------:|------------------------------:|-----------------------:|--------------------:|---------------:|
| 1. **HA Controller** + UPS                              |       1 | Intel NUC + APC 600VA        |    \$900       | 3 hrs (retrofit)             | \$375                        | \$900                 | \$375              | \$1,275        |
| 2. **Smart Thermostat** (1 zone)                        |       1 | Ecobee SmartThermostat Pro   |    \$250       | 1.5 hrs                      | \$187.50                     | \$250                 | \$187.50           | \$437.50       |
| 3. **Lighting Upgrade** (Smart Switch + Scenes)         |       1 | Lutron Vive Starter Kit      |    \$700       | 4 hrs (replacing old switches)| \$500                        | \$700                 | \$500              | \$1,200        |
| 4. **LED Fixture Replacements** (key areas)             |       6 | 4" LED Retrofits, Dimmable   |    \$40        | 1 hr each                    | \$125 ea * 6 → \$750         | \$240                 | \$750              | \$990          |
| 5. **Security Cameras** (2 interior, 1 exterior)         |       3 | Ubiquiti UniFi G4 Bullet     |    \$160       | 1 hr each                    | \$125 ea * 3 → \$375         | \$480                 | \$375              | \$855          |
| 6. **Access Control** (rear door keypad + sensor)       |       1 | Kisi Retrofit Keypad         |    \$600       | 4 hrs (existing door wiring) | \$500                        | \$600                 | \$500              | \$1,100        |
| 7. **Network Switch** (8-port PoE)                      |       1 | Ubiquiti UniFi Switch 8      |    \$300       | 2 hrs                        | \$250                        | \$300                 | \$250              | \$550          |
| 8. **Installation Supplies**                             |   n/a   | (Cables, connectors)         |    \$150       | --                           | --                           | \$150                 | --                 | \$150          |
| 9. **Programming & Commissioning**                      |   n/a   | (Scene setup, testing)       |    --          | 6 hrs total                  | \$750                        | --                    | \$750              | \$750          |
| **Subtotal Hardware**                                   |         |                              |               |                              |                               | **\$3,620**           |                    |               |
| **Subtotal Labor**                                      |         |                              |               |                              |                               |                       | **\$3,687.50**     |               |
| **Total Estimated**                                     |         |                              |               |                              |                               |                       |                    | **\$7,307.50**|

**Scope & Features**:
- **Lighting**: Replace older switches with Lutron Vive kit for scheduling, basic occupancy triggers.  
- **Limited Fixture Replacement**: Focus on prime display areas and fitting zone to modernize look.  
- **Security**: 3 cameras integrated into the same HA dashboard as lighting/HVAC.  
- **Minimal Access Control**: Retrofit keypad + sensor for staff's back door.  
- **Central Management**: Store manager uses a tablet for scene changes, music control (optional), etc.

---

## 3) CoWork Nook (Downtown Los Angeles)

### A. **New Build Proposal**  
**Scenario**: CoWork Nook is building out a **new** 6,000 sq ft co-working loft. They want advanced occupant sensors, multi-zone HVAC, and flexible access for members.

| **Item**                                                 | **Qty** | **Brand / Model**                           | **Unit Price** | **Est. Labor** <br>(hrs each) | **Labor Cost** <br>(\$125/hr) | **Hardware Subtotal** | **Labor Subtotal** | **Line Total** |
|----------------------------------------------------------|--------:|---------------------------------------------|---------------:|------------------------------:|------------------------------:|-----------------------:|--------------------:|---------------:|
| 1. **HA Controller** + Redundant Mini PC + UPS          |       1 | Intel NUC + 2nd backup unit + APC 900VA     |  \$1,500       | 3 hrs                        | \$375                        | \$1,500               | \$375              | \$1,875        |
| 2. **Multi-Zone Smart Thermostats** (4 zones)           |       4 | Ecobee SmartThermostat Pro                  |   \$250        | 1 hr each                    | \$125 ea * 4 → \$500         | \$1,000               | \$500              | \$1,500        |
| 3. **Occupancy Sensors** (desk areas, private rooms)    |      12 | Lutron Vive Radio Powr Savr                |   \$100        | 0.75 hr each                 | \$93.75 ea * 12 → \$1,125     | \$1,200               | \$1,125            | \$2,325        |
| 4. **Lighting Control Hubs** (2 for the loft)           |       2 | Lutron Vive Hub                             |   \$400        | 2 hrs each                   | \$250 ea * 2 → \$500         | \$800                 | \$500              | \$1,300        |
| 5. **LED Fixtures** (open space + meeting rooms)        |      25 | Commercial 2x4 LED Panels, Dimmable         |    \$90        | 0.5 hr each                  | \$62.50 ea * 25 → \$1,562.50  | \$2,250               | \$1,562.50         | \$3,812.50     |
| 6. **Access Control** (2 main doors + 2 private offices)|       4 | Kisi Pro + 4 RFID readers                  |  \$1,200       | 1.5 hrs each                 | \$187.50 ea * 4 → \$750      | \$4,800               | \$750              | \$5,550        |
| 7. **Security Cameras** (6 coverage points)             |       6 | Ubiquiti UniFi G4 Dome                     |   \$180        | 1 hr each                    | \$125 ea * 6 → \$750         | \$1,080               | \$750              | \$1,830        |
| 8. **Conference Room AV Kits** (2 rooms)                |       2 | Logitech Rally Bar (video conf system)      |  \$1,800       | 2 hrs each                   | \$250 ea * 2 → \$500         | \$3,600               | \$500              | \$4,100        |
| 9. **Network Switches** (2 x 16-port PoE)               |       2 | Ubiquiti UniFi Switch 16 (150W)            |   \$500        | 3 hrs each                   | \$375 ea * 2 → \$750         | \$1,000               | \$750              | \$1,750        |
| 10. **Installation Supplies**                            |   n/a   | (Cables, connectors, etc.)                 |   \$600        | --                           | --                           | \$600                 | --                 | \$600          |
| 11. **Programming & Commissioning**                     |   n/a   | (Automation logic, occupant analytics)      |   --           | 12 hrs total                 | \$1,500                      | --                    | \$1,500            | \$1,500        |
| **Subtotal Hardware**                                   |         |                                             |               |                              |                               | **\$17,830**          |                    |               |
| **Subtotal Labor**                                      |         |                                             |               |                              |                               |                       | **\$7,812.50**     |               |
| **Total Estimated**                                     |         |                                             |               |                              |                               |                       |                    | **\$25,642.50**|

**Scope & Features**:
- **Redundant HA Setup**: Minimizes downtime.  
- **Occupancy-Based Zoning**: Efficient HVAC scheduling.  
- **Flexible Access**: 2 main entrances + 2 private offices with RFID or mobile keys.  
- **Meeting Rooms**: Basic AV integration for video conferencing, integrated lighting scenes.  
- **Security**: 6 cameras for general coverage, integrated with occupancy sensors for after-hours.  
- **Open-Plan Lighting**: Dimmable overhead fixtures, motion sensors in quiet corners.

---

### B. **Renovation Proposal**  
**Scenario**: CoWork Nook has an **existing** 6,000 sq ft space that they're partially renovating (new flooring, reconfiguring open desk areas). We'll add multi-zone thermostats, occupant sensors, and upgrade existing door locks.

| **Item**                                                 | **Qty** | **Brand / Model**                          | **Unit Price** | **Est. Labor** <br>(hrs each) | **Labor Cost** <br>(\$125/hr) | **Hardware Subtotal** | **Labor Subtotal** | **Line Total** |
|----------------------------------------------------------|--------:|--------------------------------------------|---------------:|------------------------------:|------------------------------:|-----------------------:|--------------------:|---------------:|
| 1. **HA Controller** + UPS                              |       1 | Intel NUC + APC 600VA                     |    \$900       | 4 hrs (retrofit complexities)| \$500                        | \$900                 | \$500              | \$1,400        |
| 2. **Smart Thermostats** (3 existing zones)             |       3 | Ecobee SmartThermostat Pro                |    \$250       | 1.5 hrs each                 | \$187.50 ea *3→ \$562.50      | \$750                 | \$562.50           | \$1,312.50     |
| 3. **Occupancy Sensors** (8 areas)                      |       8 | Lutron Vive Radio Powr Savr              |    \$100       | 1 hr each                    | \$125 ea * 8 → \$1,000        | \$800                 | \$1,000            | \$1,800        |
| 4. **Lighting Control Hub** (1 main)                    |       1 | Lutron Vive Hub                           |    \$400       | 3 hrs                        | \$375                        | \$400                 | \$375              | \$775          |
| 5. **Lighting Retrofit** (select open desk + conference)|      15 | 2x4 LED Retrofit Panels, Dimmable         |     \$80       | 1 hr each                    | \$125 ea *15→ \$1,875         | \$1,200               | \$1,875            | \$3,075        |
| 6. **Access Control** (2 main doors)                    |       2 | Kisi Retrofit Kits                        |    \$900       | 4 hrs each                   | \$500 ea *2 → \$1,000         | \$1,800               | \$1,000            | \$2,800        |
| 7. **Security Cameras** (4 coverage points)             |       4 | Ubiquiti UniFi G4 Dome                   |    \$180       | 1.5 hrs each                 | \$187.50 ea *4→\$750          | \$720                 | \$750              | \$1,470        |
| 8. **Network Switch** (16-port PoE)                     |       1 | Ubiquiti UniFi Switch 16 (150W)          |    \$500       | 3 hrs                        | \$375                        | \$500                 | \$375              | \$875          |
| 9. **Installation Supplies**                             |   n/a   | (Cables, connectors)                     |    \$400       | --                           | --                           | \$400                 | --                 | \$400          |
| 10. **Programming & Commissioning**                     |   n/a   | (Automation, occupant analytics)          |    --          | 10 hrs total                 | \$1,250                      | --                    | \$1,250            | \$1,250        |
| **Subtotal Hardware**                                   |         |                                           |               |                              |                               | **\$6,470**           |                    |               |
| **Subtotal Labor**                                      |         |                                           |               |                              |                               |                       | **\$7,687.50**     |               |
| **Total Estimated**                                     |         |                                           |               |                              |                               |                       |                    | **\$14,157.50**|

**Scope & Features**:
- **Retrofitting** existing lights in key zones for occupancy-based dimming.  
- **Partial Access Control** for main entrances only.  
- **Cameras** for key communal areas. Possibly reusing some existing wiring, but labor includes tracing cables.  
- **Slightly fewer occupant sensors** than new build but enough to capture main zones.  
- **HA** integration for a single user interface. Occupant analytics can track usage, but some limitations due to older layout constraints.

---

## Notes & Assumptions

1. **Labor Rate**: All labor at **\$125/hour** for commercial technician. More specialized tasks (e.g., advanced configuration) are billed at the same rate for simplicity here.  
2. **Wiring Complexity**: Retrofits generally require **more** hours than new builds, reflecting cable fishing, working around existing walls, etc.  
3. **Hardware Margins**: Each item is shown at approximate **retail** or "street" pricing. In practice, you might have integrator discounts and markups, but these tables reflect final cost to the client.  
4. **Add-ons**: These proposals do **not** include additional software subscription costs (e.g. advanced cloud features from Lutron or Kisi). Some clients may also want extended warranties or premium support.  
5. **Scalable**: In each scenario, we can expand the number of sensors, thermostats, or access points over time as the client grows.  
6. **Misc.**: We assume Internet connectivity is provided by the client or local ISP. No major structural changes or advanced custom finishing (like hidden in-wall cable raceways) beyond typical commercial norms are included.  

---

### How These Proposals Aid Sales & Planning

- **Budget Transparency**: Each table clarifies hardware vs. labor, giving the client a clear sense of where costs arise.  
- **Tailored Functionality**: By itemizing components (thermostats, sensors, cameras), we can easily scale up/down based on final design.  
- **Advanced Yet Commoditized**: Selections like Ubiquiti UniFi for cameras/switches, Ecobee or Lutron for thermostats/lighting, and Kisi for access control keep costs moderate while providing robust commercial-grade capabilities.  
- **Future Expandability**: Because everything runs on a Home Assistant core (with supporting brand hubs like Lutron Vive or Kisi), adding more sensors, rooms, or advanced AI features is straightforward in subsequent phases.  

These six proposals (New Build + Renovation for each of the three Year 1–2 commercial profiles) illustrate typical "average scope" projects. Real-world quotes would be fine-tuned after a site survey or architectural review, but these examples show how we might scope out hardware, labor, and advanced functionality while using widely available commercial products.

Perfect. I'll now develop significantly expanded, itemized proposals for both New Build and Renovation service scopes for each of the Year 3–4 commercial customer profiles: Horizon Charter Middle School, BridgeWave Tech Solutions, and Valley Township Municipal Complex. Each will include specific commercial-grade hardware, advanced functionality, retail pricing, and labor at a flat $125/hour rate. I'll return with full proposals shortly.

# Year 3–4 Smart Building Proposals

Below are detailed proposals for **New Build** and **Renovation** service tiers for each Year 3–4 commercial client profile. Each proposal addresses expanded scope and complexity (versus Year 1–2) with multi-zone HVAC, occupancy-based lighting, role-based access control, security camera systems, centralized dashboards/analytics, and scalable infrastructure. Solutions favor commercial off-the-shelf products for cost-effectiveness. Hardware, quantities, unit pricing, functions, labor estimates (@ $125/hr), and cost breakdowns are provided for each scenario.

## Horizon Charter Middle School (Santa Ana, CA)

**Facility Profile:** A mid-sized charter middle school with multiple classrooms, offices, and common areas. The aim is to improve comfort and security campus-wide. 

### New Build Proposal

In this ground-up scenario, the design incorporates networked multi-zone HVAC control for classrooms and offices, wireless occupancy sensors for automated classroom lighting, and a robust security system for campus entry points. A unified management platform (Niagara Framework) ties HVAC, lighting, access control, and cameras into one dashboard with analytics (e.g. energy usage trends, occupancy patterns). Commodity hardware (e.g. Honeywell BACnet thermostats, Lutron Vive lighting controls) keeps costs reasonable while ensuring scalability.

| Component (Brand/Model)                         | Qty | Unit Price                   | Hardware Subtotal | Labor (hrs/ea) | Labor (hrs total) | Labor Cost  | Function                                                     |
| ---                                            | --- | ---                          | ---               | ---            | ---               | ---         | ---                                                         |
| Thermostat (Honeywell BACnet TB3026B)           | 12  | $350 ****      | $4,200            | 2              | 24                | $3,000     | HVAC zone temperature control (networked)                    |
| Occupancy Sensor (Lutron Vive wireless ceiling) | 20  | $100 ** ([Lutron Electronics|LRF2-OCR2B-P-WH|027557831970 - Butler Supply](https://www.butlersupply.com/lutron-electronics-lrf2-ocr2b-p-wh-118709-97#:~:text=Lutron%20Electronics%7CLRF2,P))**       | $2,000            | 0.5            | 10                | $1,250     | Detect occupancy to control lights (auto-off)                |
| Lighting Control Module (Lutron Vive PowPak relay) | 20 | $70 ****       | $1,400            | 1              | 20                | $2,500     | Switch/dim lights per sensor or schedule                     |
| Vive Lighting Hub (BACnet integration)          | 1   | $1,500 ** ([Lutron HJS-2-FM Vive Wireless Hub Lighting Control System](https://lighting.wallplate.org/lutron-hjs-2-fm-vive-wireless-hub-lighting.html#:~:text=Lutron%20HJS,1400%24%20which%20is%20a))**     | $1,500            | 2              | 2                 | $250       | Central lighting control; BACnet link to BMS                 |
| Door Controller (Axis A1001, 2-door)            | 3   | $600 ** ([AXIS A1001 Network Door Controller BULK (10 Pieces) , 0540-021](https://www.affinitechstore.com/axis-a1001-network-door-controller-bulk-10-pieces-0540-021/?srsltid=AfmBOoqVrVdzdeCBzSnfY9CvrPSKhL74HWsKvhdf2RyOK7xOdrKds0BR#:~:text=AXIS%20A1001%20Network%20Door%20Controller,00))**       | $1,800            | 2              | 6                 | $750       | Network access controller (up to 2 doors)                    |
| Card Reader (HID multiCLASS RP40)               | 6   | $300 ****        | $1,800            | 1              | 6                 | $750       | RFID card reader for doors (role-based access)               |
| Electronic Door Strike (HES electric strike)    | 6   | $250 ** ([HES 9600 Electric Strike. The Stylish Windstorm Resistant, Surface ...](https://www.amazon.com/HES-Windstorm-Resistant-Solution-Stainless/dp/B07PYGLTFT#:~:text=,Subtotal))**       | $1,500            | 2              | 12                | $1,500     | Electric door latch hardware (remote unlock)                 |
| Door Sensors (REX + contact per door)           | 6   | $100                         | $600             | 1              | 6                 | $750       | Exit motion sensor & door status contact                     |
| Indoor IP Camera (Axis M3086-V, 4MP)            | 10  | $384 ** ([AXIS M30 Series M3086-V Mic - network surveillance camera - dome](https://www.insight.com/en_US/shop/product/02832-001/axis%20communications/02832-001/AXIS-M30-Series-M3086V-Mic-network-surveillance-camera-dome/#:~:text=dome%20www,dome))**       | $3,840            | 2              | 20                | $2,500     | Indoor surveillance camera (1080p/4MP, IR)                   |
| Outdoor IP Camera (Axis M2026-LE, 4MP)          | 6   | $432 ** ([Axis M2026-Le Fixed Ip Camera Quad Hd 14 0912-001 | Zoro](https://www.zoro.com/axis-m2026-le-fixed-ip-camera-quad-hd-14-0912-001/i/G2523557/#:~:text=Axis%20M2026,Add%20to%20Cart%2C%20Main))**       | $2,592            | 3              | 18                | $2,250     | Outdoor IP camera (4MP, IR, weatherproof)                    |
| NVR Server & Storage (for 16 cams/30 days)      | 1   | $3,000                       | $3,000            | 4              | 4                 | $500       | Video recording server (≈30-day storage)                     |
| Integration Controller (Tridium JACE-8000)      | 1   | $2,000 ****        | $2,000            | 32             | 32                | $4,000     | Unified building management controller/dashboard             |
| Network PoE Switch (24-port, Gigabit)           | 1   | $800                         | $800             | 1              | 1                 | $125       | PoE network switch for cameras & devices                     |

- **Hardware Subtotal:** $27,032  
- **Labor Subtotal:** 161.0 hrs = $20,125 (@$125/hr)  
- **Total Estimated Cost:** $47,157  

### Renovation Proposal

For the retrofit scenario, the approach upgrades the existing school with minimal disruption. Wireless sensors (Lutron Vive) and controllers are added to existing lighting circuits, enabling occupancy-based lighting without re-wiring. Existing HVAC units are outfitted with BACnet thermostats for multi-zone scheduling. The access control and surveillance systems are layered onto current doors and IT infrastructure. The Niagara-based dashboard integrates old and new systems for centralized monitoring. Labor hours are higher due to working in an occupied building (e.g. installing strikes in existing doors, fishing cables), but the design avoids major renovations by using modular, wireless components.

| Component (Brand/Model)                         | Qty | Unit Price                   | Hardware Subtotal | Labor (hrs/ea) | Labor (hrs total) | Labor Cost  | Function                                                     |
| ---                                            | --- | ---                          | ---               | ---            | ---               | ---         | ---                                                         |
| Thermostat (Honeywell BACnet TB3026B)           | 12  | $350 ****      | $4,200            | 3              | 36                | $4,500     | HVAC zone temperature control (networked)                    |
| Occupancy Sensor (Lutron Vive wireless ceiling) | 20  | $100 ** ([Lutron Electronics|LRF2-OCR2B-P-WH|027557831970 - Butler Supply](https://www.butlersupply.com/lutron-electronics-lrf2-ocr2b-p-wh-118709-97#:~:text=Lutron%20Electronics%7CLRF2,P))**       | $2,000            | 0.5            | 10                | $1,250     | Detect occupancy to control lights (auto-off)                |
| Lighting Control Module (Lutron Vive PowPak relay) | 20 | $70 ****       | $1,400            | 1.5            | 30                | $3,750     | Switch/dim lights per sensor or schedule                     |
| Vive Lighting Hub (BACnet integration)          | 1   | $1,500 ** ([Lutron HJS-2-FM Vive Wireless Hub Lighting Control System](https://lighting.wallplate.org/lutron-hjs-2-fm-vive-wireless-hub-lighting.html#:~:text=Lutron%20HJS,1400%24%20which%20is%20a))**     | $1,500            | 2              | 2                 | $250       | Central lighting control; BACnet link to BMS                 |
| Door Controller (Axis A1001, 2-door)            | 3   | $600 ** ([AXIS A1001 Network Door Controller BULK (10 Pieces) , 0540-021](https://www.affinitechstore.com/axis-a1001-network-door-controller-bulk-10-pieces-0540-021/?srsltid=AfmBOoqVrVdzdeCBzSnfY9CvrPSKhL74HWsKvhdf2RyOK7xOdrKds0BR#:~:text=AXIS%20A1001%20Network%20Door%20Controller,00))**       | $1,800            | 3              | 9                 | $1,125     | Network access controller (up to 2 doors)                    |
| Card Reader (HID multiCLASS RP40)               | 6   | $300 ****        | $1,800            | 1.5            | 9                 | $1,125     | RFID card reader for doors (role-based access)               |
| Electronic Door Strike (HES electric strike)    | 6   | $250 ** ([HES 9600 Electric Strike. The Stylish Windstorm Resistant, Surface ...](https://www.amazon.com/HES-Windstorm-Resistant-Solution-Stainless/dp/B07PYGLTFT#:~:text=,Subtotal))**       | $1,500            | 3              | 18                | $2,250     | Electric door latch hardware (remote unlock)                 |
| Door Sensors (REX + contact per door)           | 6   | $100                         | $600             | 1.5            | 9                 | $1,125     | Exit motion sensor & door status contact                     |
| Indoor IP Camera (Axis M3086-V, 4MP)            | 10  | $384 ** ([AXIS M30 Series M3086-V Mic - network surveillance camera - dome](https://www.insight.com/en_US/shop/product/02832-001/axis%20communications/02832-001/AXIS-M30-Series-M3086V-Mic-network-surveillance-camera-dome/#:~:text=dome%20www,dome))**       | $3,840            | 3              | 30                | $3,750     | Indoor surveillance camera (1080p/4MP, IR)                   |
| Outdoor IP Camera (Axis M2026-LE, 4MP)          | 6   | $432 ** ([Axis M2026-Le Fixed Ip Camera Quad Hd 14 0912-001 | Zoro](https://www.zoro.com/axis-m2026-le-fixed-ip-camera-quad-hd-14-0912-001/i/G2523557/#:~:text=Axis%20M2026,Add%20to%20Cart%2C%20Main))**       | $2,592            | 4              | 24                | $3,000     | Outdoor IP camera (4MP, IR, weatherproof)                    |
| NVR Server & Storage (for 16 cams/30 days)      | 1   | $3,000                       | $3,000            | 4              | 4                 | $500       | Video recording server (≈30-day storage)                     |
| Integration Controller (Tridium JACE-8000)      | 1   | $2,000 ****        | $2,000            | 36             | 36                | $4,500     | Unified building management controller/dashboard             |
| Network PoE Switch (24-port, Gigabit)           | 1   | $800                         | $800             | 1              | 1                 | $125       | PoE network switch for cameras & devices                     |

- **Hardware Subtotal:** $27,032  
- **Labor Subtotal:** 218.0 hrs = $27,250 (@$125/hr)  
- **Total Estimated Cost:** $54,282  

## BridgeWave Tech Solutions (Irvine, CA)

**Facility Profile:** A technology solutions company office (approx. 50 employees) with open plan workspaces, conference rooms, a server lab, and secured entrances. The goal is to enhance energy efficiency and security while allowing future expansion.

### New Build Proposal

For a new office build, the design emphasizes IP-based infrastructure and flexibility. **Multi-zone HVAC** is implemented with smart thermostats in different office areas and a server room for precise climate control. **Occupancy sensors** turn off lights in empty conference rooms and adjust open-area lighting after hours. A **role-based access control** system secures all entry points (e.g. front door, back door, lab) with HID badge readers tied to employee roles. **High-resolution IP cameras** monitor entrances and critical interior zones, recording to an on-site NVR with ~30 days retention. All systems integrate into a central dashboard (accessible to facility IT staff) that provides real-time status and analytics (such as room occupancy trends and HVAC runtime data). Standard network hardware (PoE switches, Cat6 wiring) supports scalable expansion (e.g. adding more cameras or sensors easily).

| Component (Brand/Model)                         | Qty | Unit Price                   | Hardware Subtotal | Labor (hrs/ea) | Labor (hrs total) | Labor Cost  | Function                                                     |
| ---                                            | --- | ---                          | ---               | ---            | ---               | ---         | ---                                                         |
| Thermostat (Honeywell BACnet TB3026B)           | 6   | $350 ****      | $2,100            | 2              | 12                | $1,500     | HVAC zone temperature control (networked)                    |
| Occupancy Sensor (Lutron Vive wireless ceiling) | 10  | $100 ** ([Lutron Electronics|LRF2-OCR2B-P-WH|027557831970 - Butler Supply](https://www.butlersupply.com/lutron-electronics-lrf2-ocr2b-p-wh-118709-97#:~:text=Lutron%20Electronics%7CLRF2,P))**       | $1,000            | 0.5            | 5                 | $625       | Detect occupancy to control lights (auto-off)                |
| Lighting Control Module (Lutron Vive PowPak relay) | 10 | $70 ****       | $700             | 1              | 10                | $1,250     | Switch/dim lights per sensor or schedule                     |
| Vive Lighting Hub (BACnet integration)          | 1   | $1,500 ** ([Lutron HJS-2-FM Vive Wireless Hub Lighting Control System](https://lighting.wallplate.org/lutron-hjs-2-fm-vive-wireless-hub-lighting.html#:~:text=Lutron%20HJS,1400%24%20which%20is%20a))**     | $1,500            | 2              | 2                 | $250       | Central lighting control; BACnet link to BMS                 |
| Door Controller (Axis A1001, 2-door)            | 2   | $600 ** ([AXIS A1001 Network Door Controller BULK (10 Pieces) , 0540-021](https://www.affinitechstore.com/axis-a1001-network-door-controller-bulk-10-pieces-0540-021/?srsltid=AfmBOoqVrVdzdeCBzSnfY9CvrPSKhL74HWsKvhdf2RyOK7xOdrKds0BR#:~:text=AXIS%20A1001%20Network%20Door%20Controller,00))**       | $1,200            | 2              | 4                 | $500       | Network access controller (up to 2 doors)                    |
| Card Reader (HID multiCLASS RP40)               | 4   | $300 ****        | $1,200            | 1              | 4                 | $500       | RFID card reader for doors (role-based access)               |
| Electronic Door Strike (HES electric strike)    | 4   | $250 ** ([HES 9600 Electric Strike. The Stylish Windstorm Resistant, Surface ...](https://www.amazon.com/HES-Windstorm-Resistant-Solution-Stainless/dp/B07PYGLTFT#:~:text=,Subtotal))**       | $1,000            | 2              | 8                 | $1,000     | Electric door latch hardware (remote unlock)                 |
| Door Sensors (REX + contact per door)           | 4   | $100                         | $400             | 1              | 4                 | $500       | Exit motion sensor & door status contact                     |
| Indoor IP Camera (Axis M3086-V, 4MP)            | 4   | $384 ** ([AXIS M30 Series M3086-V Mic - network surveillance camera - dome](https://www.insight.com/en_US/shop/product/02832-001/axis%20communications/02832-001/AXIS-M30-Series-M3086V-Mic-network-surveillance-camera-dome/#:~:text=dome%20www,dome))**       | $1,536            | 2              | 8                 | $1,000     | Indoor surveillance camera (1080p/4MP, IR)                   |
| Outdoor IP Camera (Axis M2026-LE, 4MP)          | 4   | $432 ** ([Axis M2026-Le Fixed Ip Camera Quad Hd 14 0912-001 | Zoro](https://www.zoro.com/axis-m2026-le-fixed-ip-camera-quad-hd-14-0912-001/i/G2523557/#:~:text=Axis%20M2026,Add%20to%20Cart%2C%20Main))**       | $1,728            | 3              | 12                | $1,500     | Outdoor IP camera (4MP, IR, weatherproof)                    |
| NVR Server & Storage (for 8 cams/30 days)       | 1   | $2,500                       | $2,500            | 4              | 4                 | $500       | Video recording server (≈30-day storage)                     |
| Integration Controller (Tridium JACE-8000)      | 1   | $2,000 ****        | $2,000            | 24             | 24                | $3,000     | Unified building management controller/dashboard             |
| Network PoE Switch (24-port, Gigabit)           | 1   | $800                         | $800             | 1              | 1                 | $125       | PoE network switch for cameras & devices                     |

- **Hardware Subtotal:** $17,664  
- **Labor Subtotal:** 98.0 hrs = $12,250 (@$125/hr)  
- **Total Estimated Cost:** $29,914  

### Renovation Proposal

The retrofit proposal upgrades BridgeWave's existing office with smart building features while leveraging current infrastructure. Wireless Lutron Vive sensors and control modules are installed in light fixtures and ceilings to implement occupancy-based lighting without rewiring. Existing single-zone HVAC thermostats are replaced with Honeywell BACnet models to enable multi-zone scheduling and remote management. The access system is added to current doors (reusing door frames with new electric strikes and readers) to provide secure, role-based entry using employee badges. IP cameras are added at key points (entry doors, server room) and tie into a new NVR. A unified Niagara dashboard overlays on top of the existing IT network, aggregating all new subsystems for centralized control and analytics. Labor is allocated for careful installation in the active office (e.g. running cables after hours, integrating with legacy equipment).

| Component (Brand/Model)                         | Qty | Unit Price                   | Hardware Subtotal | Labor (hrs/ea) | Labor (hrs total) | Labor Cost  | Function                                                     |
| ---                                            | --- | ---                          | ---               | ---            | ---               | ---         | ---                                                         |
| Thermostat (Honeywell BACnet TB3026B)           | 6   | $350 ****      | $2,100            | 3              | 18                | $2,250     | HVAC zone temperature control (networked)                    |
| Occupancy Sensor (Lutron Vive wireless ceiling) | 10  | $100 **【15†L37-L41}**        | $1,000            | 0.5            | 5                 | $625       | Detect occupancy to control lights (auto-off)                |
| Lighting Control Module (Lutron Vive PowPak relay) | 10 | $70 ****       | $700             | 1.5            | 15                | $1,875     | Switch/dim lights per sensor or schedule                     |
| Vive Lighting Hub (BACnet integration)          | 1   | $1,500 ** ([Lutron HJS-2-FM Vive Wireless Hub Lighting Control System](https://lighting.wallplate.org/lutron-hjs-2-fm-vive-wireless-hub-lighting.html#:~:text=Lutron%20HJS,1400%24%20which%20is%20a))**     | $1,500            | 2              | 2                 | $250       | Central lighting control; BACnet link to BMS                 |
| Door Controller (Axis A1001, 2-door)            | 2   | $600 ** ([AXIS A1001 Network Door Controller BULK (10 Pieces) , 0540-021](https://www.affinitechstore.com/axis-a1001-network-door-controller-bulk-10-pieces-0540-021/?srsltid=AfmBOoqVrVdzdeCBzSnfY9CvrPSKhL74HWsKvhdf2RyOK7xOdrKds0BR#:~:text=AXIS%20A1001%20Network%20Door%20Controller,00))**       | $1,200            | 3              | 6                 | $750       | Network access controller (up to 2 doors)                    |
| Card Reader (HID multiCLASS RP40)               | 4   | $300 ****        | $1,200            | 1.5            | 6                 | $750       | RFID card reader for doors (role-based access)               |
| Electronic Door Strike (HES electric strike)    | 4   | $250 ** ([HES 9600 Electric Strike. The Stylish Windstorm Resistant, Surface ...](https://www.amazon.com/HES-Windstorm-Resistant-Solution-Stainless/dp/B07PYGLTFT#:~:text=,Subtotal))**       | $1,000            | 3              | 12                | $1,500     | Electric door latch hardware (remote unlock)                 |
| Door Sensors (REX + contact per door)           | 4   | $100                         | $400             | 1.5            | 6                 | $750       | Exit motion sensor & door status contact                     |
| Indoor IP Camera (Axis M3086-V, 4MP)            | 4   | $384 ** ([AXIS M30 Series M3086-V Mic - network surveillance camera - dome](https://www.insight.com/en_US/shop/product/02832-001/axis%20communications/02832-001/AXIS-M30-Series-M3086V-Mic-network-surveillance-camera-dome/#:~:text=dome%20www,dome))**       | $1,536            | 3              | 12                | $1,500     | Indoor surveillance camera (1080p/4MP, IR)                   |
| Outdoor IP Camera (Axis M2026-LE, 4MP)          | 4   | $432 ** ([Axis M2026-Le Fixed Ip Camera Quad Hd 14 0912-001 | Zoro](https://www.zoro.com/axis-m2026-le-fixed-ip-camera-quad-hd-14-0912-001/i/G2523557/#:~:text=Axis%20M2026,Add%20to%20Cart%2C%20Main))**       | $1,728            | 4              | 16                | $2,000     | Outdoor IP camera (4MP, IR, weatherproof)                    |
| NVR Server & Storage (for 8 cams/30 days)       | 1   | $2,500                       | $2,500            | 4              | 4                 | $500       | Video recording server (≈30-day storage)                     |
| Integration Controller (Tridium JACE-8000)      | 1   | $2,000 ****        | $2,000            | 28             | 28                | $3,500     | Unified building management controller/dashboard             |
| Network PoE Switch (24-port, Gigabit)           | 1   | $800                         | $800             | 1              | 1                 | $125       | PoE network switch for cameras & devices                     |

- **Hardware Subtotal:** $17,664  
- **Labor Subtotal:** 128.0 hrs = $16,000 (@$125/hr)  
- **Total Estimated Cost:** $33,664  

## Valley Township Municipal Complex (Bakersfield, CA region)

**Facility Profile:** A new municipal complex (e.g. city hall and civic offices) comprising offices, meeting chambers, and public service areas. Security and centralized management are top priorities, given the need to protect sensitive areas and manage multiple building zones.

### New Build Proposal

In a new municipal complex, the smart building design scales to a larger facility with many zones and entry points. **HVAC is divided into 8 zones** (e.g. lobby, offices, council chamber, etc.) each with a networked thermostat for independent control and scheduling. **Occupancy sensors** are placed in offices, hallways, and restrooms to ensure lights are off when areas are unoccupied (significant energy savings in a 24/7 public facility). A comprehensive **access control system** secures all exterior doors and restricted interior areas (archives, IT rooms), using card readers to differentiate access levels for employees vs. public. Over a dozen **IP security cameras** cover building entrances, parking lots, and interior corridors, feeding into an NVR system for video retention and remote monitoring. All subsystems integrate into a Niagara-based central management console in the facility control room, allowing facilities staff to monitor HVAC status, adjust lighting schedules, review access logs, and view camera feeds/analytics on one dashboard. The network infrastructure (gigabit PoE switching, fiber uplinks if needed) is designed for scalability, so additional cameras or IoT sensors (e.g. for future buildings or parking areas) can be added easily.

| Component (Brand/Model)                         | Qty | Unit Price                   | Hardware Subtotal | Labor (hrs/ea) | Labor (hrs total) | Labor Cost  | Function                                                     |
| ---                                            | --- | ---                          | ---               | ---            | ---               | ---         | ---                                                         |
| Thermostat (Honeywell BACnet TB3026B)           | 8   | $350 ****      | $2,800            | 2              | 16                | $2,000     | HVAC zone temperature control (networked)                    |
| Occupancy Sensor (Lutron Vive wireless ceiling) | 15  | $100 ** ([Lutron Electronics|LRF2-OCR2B-P-WH|027557831970 - Butler Supply](https://www.butlersupply.com/lutron-electronics-lrf2-ocr2b-p-wh-118709-97#:~:text=Lutron%20Electronics%7CLRF2,P))**       | $1,500            | 0.5            | 7.5               | $938       | Detect occupancy to control lights (auto-off)                |
| Lighting Control Module (Lutron Vive PowPak relay) | 15 | $70 ****       | $1,050            | 1              | 15                | $1,875     | Switch/dim lights per sensor or schedule                     |
| Vive Lighting Hub (BACnet integration)          | 1   | $1,500 ** ([Lutron HJS-2-FM Vive Wireless Hub Lighting Control System](https://lighting.wallplate.org/lutron-hjs-2-fm-vive-wireless-hub-lighting.html#:~:text=Lutron%20HJS,1400%24%20which%20is%20a))**     | $1,500            | 2              | 2                 | $250       | Central lighting control; BACnet link to BMS                 |
| Door Controller (Axis A1001, 2-door)            | 4   | $600 ** ([AXIS A1001 Network Door Controller BULK (10 Pieces) , 0540-021](https://www.affinitechstore.com/axis-a1001-network-door-controller-bulk-10-pieces-0540-021/?srsltid=AfmBOoqVrVdzdeCBzSnfY9CvrPSKhL74HWsKvhdf2RyOK7xOdrKds0BR#:~:text=AXIS%20A1001%20Network%20Door%20Controller,00))**       | $2,400            | 2              | 8                 | $1,000     | Network access controller (up to 2 doors)                    |
| Card Reader (HID multiCLASS RP40)               | 8   | $300 ****        | $2,400            | 1              | 8                 | $1,000     | RFID card reader for doors (role-based access)               |
| Electronic Door Strike (HES electric strike)    | 8   | $250 ** ([HES 9600 Electric Strike. The Stylish Windstorm Resistant, Surface ...](https://www.amazon.com/HES-Windstorm-Resistant-Solution-Stainless/dp/B07PYGLTFT#:~:text=,Subtotal))**       | $2,000            | 2              | 16                | $2,000     | Electric door latch hardware (remote unlock)                 |
| Door Sensors (REX + contact per door)           | 8   | $100                         | $800             | 1              | 8                 | $1,000     | Exit motion sensor & door status contact                     |
| Indoor IP Camera (Axis M3086-V, 4MP)            | 12  | $384 ** ([AXIS M30 Series M3086-V Mic - network surveillance camera - dome](https://www.insight.com/en_US/shop/product/02832-001/axis%20communications/02832-001/AXIS-M30-Series-M3086V-Mic-network-surveillance-camera-dome/#:~:text=dome%20www,dome))**       | $4,608            | 2              | 24                | $3,000     | Indoor surveillance camera (1080p/4MP, IR)                   |
| Outdoor IP Camera (Axis M2026-LE, 4MP)          | 8   | $432 ** ([Axis M2026-Le Fixed Ip Camera Quad Hd 14 0912-001 | Zoro](https://www.zoro.com/axis-m2026-le-fixed-ip-camera-quad-hd-14-0912-001/i/G2523557/#:~:text=Axis%20M2026,Add%20to%20Cart%2C%20Main))**       | $3,456            | 3              | 24                | $3,000     | Outdoor IP camera (4MP, IR, weatherproof)                    |
| NVR Server & Storage (for 20 cams/30 days)      | 1   | $3,500                       | $3,500            | 4              | 4                 | $500       | Video recording server (≈30-day storage)                     |
| Integration Controller (Tridium JACE-8000)      | 1   | $2,000 ****        | $2,000            | 40             | 40                | $5,000     | Unified building management controller/dashboard             |
| Network PoE Switch (48-port, Gigabit)           | 1   | $1,500                       | $1,500            | 1              | 1                 | $125       | High-capacity PoE network switch (scalable)                  |

- **Hardware Subtotal:** $23,514  
- **Labor Subtotal:** 165.5 hrs = $20,688 (@$125/hr)  
- **Total Estimated Cost:** $44,202  

### Renovation Proposal

Upgrading an existing municipal complex to this advanced level involves integrating new systems with legacy building elements. The renovation plan calls for installing BACnet thermostats on existing HVAC equipment to create multi-zone control without replacing entire units. Wireless Lutron Vive sensors and modules are added to existing lighting circuits across the facility (offices, hallways) to implement occupancy-based lighting in line with California Title 24 energy codes. The access control retrofit secures 8 key doors – existing locks are replaced with electric strikes and tied into Axis controllers and HID readers, enabling role-based access for staff and logging of entry/exit times (meeting public safety requirements). A comprehensive camera system is added, utilizing existing cable pathways where possible to place indoor and outdoor IP cameras for security surveillance. A Niagara integration controller interfaces with any existing building systems (like legacy alarms or HVAC controllers) and the new devices, providing a single-pane-of-glass dashboard for facility managers. Labor estimates account for complexities like working around business hours, retrofitting door hardware in old frames, and interfacing with any legacy control wiring.

| Component (Brand/Model)                         | Qty | Unit Price                   | Hardware Subtotal | Labor (hrs/ea) | Labor (hrs total) | Labor Cost  | Function                                                     |
| ---                                            | --- | ---                          | ---               | ---            | ---               | ---         | ---                                                         |
| Thermostat (Honeywell BACnet TB3026B)           | 8   | $350 ****      | $2,800            | 3              | 24                | $3,000     | HVAC zone temperature control (networked)                    |
| Occupancy Sensor (Lutron Vive wireless ceiling) | 15  | $100 ** ([Lutron Electronics|LRF2-OCR2B-P-WH|027557831970 - Butler Supply](https://www.butlersupply.com/lutron-electronics-lrf2-ocr2b-p-wh-118709-97#:~:text=Lutron%20Electronics%7CLRF2,P))**       | $1,500            | 0.5            | 7.5               | $938       | Detect occupancy to control lights (auto-off)                |
| Lighting Control Module (Lutron Vive PowPak relay) | 15 | $70 ****       | $1,050            | 1.5            | 22.5              | $2,813     | Switch/dim lights per sensor or schedule                     |
| Vive Lighting Hub (BACnet integration)          | 1   | $1,500 ** ([Lutron HJS-2-FM Vive Wireless Hub Lighting Control System](https://lighting.wallplate.org/lutron-hjs-2-fm-vive-wireless-hub-lighting.html#:~:text=Lutron%20HJS,1400%24%20which%20is%20a))**     | $1,500            | 2              | 2                 | $250       | Central lighting control; BACnet link to BMS                 |
| Door Controller (Axis A1001, 2-door)            | 4   | $600 ** ([AXIS A1001 Network Door Controller BULK (10 Pieces) , 0540-021](https://www.affinitechstore.com/axis-a1001-network-door-controller-bulk-10-pieces-0540-021/?srsltid=AfmBOoqVrVdzdeCBzSnfY9CvrPSKhL74HWsKvhdf2RyOK7xOdrKds0BR#:~:text=AXIS%20A1001%20Network%20Door%20Controller,00))**       | $2,400            | 3              | 12                | $1,500     | Network access controller (up to 2 doors)                    |
| Card Reader (HID multiCLASS RP40)               | 8   | $300 ****        | $2,400            | 1.5            | 12                | $1,500     | RFID card reader for doors (role-based access)               |
| Electronic Door Strike (HES electric strike)    | 8   | $250 ** ([HES 9600 Electric Strike. The Stylish Windstorm Resistant, Surface ...](https://www.amazon.com/HES-Windstorm-Resistant-Solution-Stainless/dp/B07PYGLTFT#:~:text=,Subtotal))**       | $2,000            | 3              | 24                | $3,000     | Electric door latch hardware (remote unlock)                 |
| Door Sensors (REX + contact per door)           | 8   | $100                         | $800             | 1.5            | 12                | $1,500     | Exit motion sensor & door status contact                     |
| Indoor IP Camera (Axis M3086-V, 4MP)            | 12  | $384 ** ([AXIS M30 Series M3086-V Mic - network surveillance camera - dome](https://www.insight.com/en_US/shop/product/02832-001/axis%20communications/02832-001/AXIS-M30-Series-M3086V-Mic-network-surveillance-camera-dome/#:~:text=dome%20www,dome))**       | $4,608            | 3              | 36                | $4,500     | Indoor surveillance camera (1080p/4MP, IR)                   |
| Outdoor IP Camera (Axis M2026-LE, 4MP)          | 8   | $432 ** ([Axis M2026-Le Fixed Ip Camera Quad Hd 14 0912-001 | Zoro](https://www.zoro.com/axis-m2026-le-fixed-ip-camera-quad-hd-14-0912-001/i/G2523557/#:~:text=Axis%20M2026,Add%20to%20Cart%2C%20Main))**       | $3,456            | 4              | 32                | $4,000     | Outdoor IP camera (4MP, IR, weatherproof)                    |
| NVR Server & Storage (for 20 cams/30 days)      | 1   | $3,500                       | $3,500            | 4              | 4                 | $500       | Video recording server (≈30-day storage)                     |
| Integration Controller (Tridium JACE-8000)      | 1   | $2,000 ****        | $2,000            | 48             | 48                | $6,000     | Unified building management controller/dashboard             |
| Network PoE Switch (48-port, Gigabit)           | 1   | $1,500                       | $1,500            | 1              | 1                 | $125       | High-capacity PoE network switch (scalable)                  |

- **Hardware Subtotal:** $23,514  
- **Labor Subtotal:** 231.0 hrs = $28,875 (@$125/hr)  
- **Total Estimated Cost:** $52,389  

Each of the above proposals uses widely available commercial-grade hardware and reasonable unit pricing (no integrator discounts applied) to deliver advanced functionality at scale. The itemized breakdowns demonstrate the scope per component, and the centralized approach (via Tridium Niagara and standard IP networking) ensures these smart building systems are **scalable** for future expansion and **integrated** for easy management.

Perfect. I'll now create high-scope, itemized New Build and Renovation proposals for each of the Year 5–7 commercial clients: Arrowhead Plaza, Grand Oak Boutique Hotel & Spa, and Pacific Healthcare Tower. These will include enterprise-level systems where appropriate (e.g. full BMS panels, commercial surveillance infrastructure, scalable network backbones), all priced at retail with labor calculated at a flat $125/hour. I'll return shortly with detailed breakdowns.

# Detailed Year 5–7 Proposals for Commercial Smart Building Projects

## Arrowhead Plaza – 20-Floor Office Tower (San Francisco, CA)  
The proposals below detail comprehensive building system upgrades for a 20-floor office tower. They cover both a **New Build** implementation (for a brand new construction) and a **Renovation** scenario (retrofitting the existing tower), reflecting enterprise-scale HVAC, lighting, access control, surveillance, and BMS integration.

### New Build Proposal  
| Component (Model) | Purpose | Qty | Unit Price | Hardware Subtotal | Labor (hrs each) | Labor Cost (@$125/hr) | Line Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| BACnet/IP HVAC Floor Controllers (multi-zone, per floor) | Manages HVAC on each floor; integrates VAVs and thermostats | 20 | $1,500.00 | $30,000.00 | 4 | $10,000.00 | $40,000.00 |
| BACnet Zone Thermostats/Sensors | Temperature sensors and zone-level control input | 120 | $200.00 | $24,000.00 | 1 | $15,000.00 | $39,000.00 |
| Central HVAC Plant Controller | Integrates main HVAC plant (chillers/boilers) with BMS | 1 | $3,000.00 | $3,000.00 | 8 | $1,000.00 | $4,000.00 |
| BMS Server & Software Platform | Central BMS with dashboards, analytics, remote override | 1 | $15,000.00 | $15,000.00 | 40 | $5,000.00 | $20,000.00 |
| Ceiling-Mount Occupancy Sensors (wired) | Detects occupancy for automatic lighting control | 160 | $80.00 | $12,800.00 | 1 | $20,000.00 | $32,800.00 |
| Daylight Sensors (wired) | Monitors ambient light for daylight harvesting | 40 | $150.00 | $6,000.00 | 1 | $5,000.00 | $11,000.00 |
| Networked Lighting Control Panels | Zonal lighting controllers for occupancy/daylight integration | 20 | $750.00 | $15,000.00 | 3 | $7,500.00 | $22,500.00 |
| Access Control System Panel (16-door capacity) | Main controller for card access; role-based permissions, elevator interface | 1 | $4,000.00 | $4,000.00 | 8 | $1,000.00 | $5,000.00 |
| Proximity Card Readers (RFID) | Secure entry readers at doors and elevators | 10 | $300.00 | $3,000.00 | 2 | $2,500.00 | $5,500.00 |
| Electronic Door Lock Hardware | Electric strikes/maglocks for controlled doors | 6 | $500.00 | $3,000.00 | 3 | $2,250.00 | $5,250.00 |
| Elevator Access Control Interface | Allows badge-based floor access control in elevators | 4 | $1,500.00 | $6,000.00 | 4 | $2,000.00 | $8,000.00 |
| Visitor Management Kiosk (touchscreen + printer) | Self-service visitor sign-in with badge printing | 1 | $2,000.00 | $2,000.00 | 4 | $500.00 | $2,500.00 |
| IP Surveillance Cameras (1080p, PoE) | Security cameras (interior/exterior) with >30-day recording | 40 | $400.00 | $16,000.00 | 2 | $10,000.00 | $26,000.00 |
| Enterprise NVR Server (30+ day storage) | Network video recorder with large storage for 40+ cameras | 1 | $15,000.00 | $15,000.00 | 16 | $2,000.00 | $17,000.00 |
| Gigabit PoE+ Network Switches (48-port) | Connects and powers IP cameras and controllers (rack-mount) | 4 | $1,500.00 | $6,000.00 | 2 | $1,000.00 | $7,000.00 |
| Server Rack Enclosure & Patch Panels | Houses network and control equipment; organized cabling | 1 | $1,500.00 | $1,500.00 | 4 | $500.00 | $2,000.00 |
| Rack-mount UPS Backup (3kVA) | Backup power for rack equipment (prevent outages) | 1 | $1,500.00 | $1,500.00 | 2 | $250.00 | $1,750.00 |
| **Totals** |  |  |  | **$163,800.00** |  | **$72,500.00** | **$236,300.00** |

### Renovation Proposal  
| Component (Model) | Purpose | Qty | Unit Price | Hardware Subtotal | Labor (hrs each) | Labor Cost (@$125/hr) | Line Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| BACnet Smart Thermostats (zone controllers) | Retrofit networked thermostats for each zone (replace legacy units) | 120 | $250.00 | $30,000.00 | 2 | $30,000.00 | $60,000.00 |
| Central HVAC Plant Integration Module | Interfaces new BMS with existing chillers/boilers | 1 | $3,000.00 | $3,000.00 | 8 | $1,000.00 | $4,000.00 |
| BMS Server & Software Platform | Central BMS (dashboards, analytics) integrating new and legacy systems | 1 | $15,000.00 | $15,000.00 | 48 | $6,000.00 | $21,000.00 |
| Wireless Occupancy Sensors (battery-powered) | Occupancy detection for lighting control (no new wiring) | 160 | $100.00 | $16,000.00 | 0.5 | $10,000.00 | $26,000.00 |
| Wireless Daylight Sensors | Ambient light sensors for daylight harvesting (wireless retrofit) | 40 | $150.00 | $6,000.00 | 0.5 | $2,500.00 | $8,500.00 |
| Wireless Lighting Control Modules (relays) | Retrofit relay controllers for existing lighting circuits | 80 | $200.00 | $16,000.00 | 1 | $10,000.00 | $26,000.00 |
| Lighting Control Wireless Hubs | Coordinates wireless sensors/modules; provides BMS interface | 4 | $600.00 | $2,400.00 | 2 | $1,000.00 | $3,400.00 |
| Access Control System Panel | Main access controller for doors/elevators (integrates with existing doors) | 1 | $4,000.00 | $4,000.00 | 10 | $1,250.00 | $5,250.00 |
| Proximity Card Readers (retrofit) | Secure readers added to existing doors and elevator cab | 10 | $300.00 | $3,000.00 | 3 | $3,750.00 | $6,750.00 |
| Electronic Door Lock Hardware | Installed maglocks/strikes on existing doors for access control | 6 | $500.00 | $3,000.00 | 4 | $3,000.00 | $6,000.00 |
| Elevator Access Control Interface | Retrofit kit for badge-controlled elevator floor access | 4 | $1,500.00 | $6,000.00 | 6 | $3,000.00 | $9,000.00 |
| Visitor Management Kiosk | Tablet-based visitor sign-in system at lobby | 1 | $2,000.00 | $2,000.00 | 4 | $500.00 | $2,500.00 |
| IP Surveillance Cameras (1080p) | New IP cameras replacing/upgrading legacy system (30+ day storage) | 40 | $400.00 | $16,000.00 | 3 | $15,000.00 | $31,000.00 |
| Enterprise NVR Server (30+ day storage) | High-capacity NVR to record all cameras for 30+ days | 1 | $15,000.00 | $15,000.00 | 16 | $2,000.00 | $17,000.00 |
| Gigabit PoE+ Network Switches (48-port) | Dedicated network switches for IP devices (added to building) | 4 | $1,500.00 | $6,000.00 | 2 | $1,000.00 | $7,000.00 |
| Equipment Rack & Patch Panels | Rack for new controllers/servers, integrated into existing IT room | 1 | $1,500.00 | $1,500.00 | 4 | $500.00 | $2,000.00 |
| Rack-mount UPS Backup (3kVA) | Backup power unit for new system rack | 1 | $1,500.00 | $1,500.00 | 2 | $250.00 | $1,750.00 |
| **Totals** |  |  |  | **$163,400.00** |  | **$87,750.00** | **$251,150.00** |

## Grand Oak Boutique Hotel & Spa (Napa Valley, CA)  
The following proposals address the needs of a boutique hotel and spa, including guest areas and separate spa facilities. Both **New Build** and **Renovation** plans provide multi-zone HVAC, smart lighting, integrated access control (covering hotel and spa buildings with elevator integration), comprehensive surveillance, and a unified BMS for energy and security management.

### New Build Proposal  
| Component (Model) | Purpose | Qty | Unit Price | Hardware Subtotal | Labor (hrs each) | Labor Cost (@$125/hr) | Line Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| BACnet HVAC Zone Controllers | Controls climate in major zones (guest floors, spa areas) | 8 | $1,500.00 | $12,000.00 | 4 | $4,000.00 | $16,000.00 |
| Zone Thermostats/Sensors | Temperature sensing and setpoint control in each zone | 8 | $200.00 | $1,600.00 | 1 | $1,000.00 | $2,600.00 |
| BMS Server & Software | Central platform for HVAC, lighting, and security management | 1 | $10,000.00 | $10,000.00 | 32 | $4,000.00 | $14,000.00 |
| Ceiling-Mount Occupancy Sensors | Detects presence in common areas for automatic lighting | 40 | $80.00 | $3,200.00 | 1 | $5,000.00 | $8,200.00 |
| Daylight Sensors | Measures daylight in lobbies/atriums for light dimming | 10 | $150.00 | $1,500.00 | 1 | $1,250.00 | $2,750.00 |
| Lighting Control Panels | Central lighting controllers (public areas, spa) linked to sensors | 6 | $750.00 | $4,500.00 | 3 | $2,250.00 | $6,750.00 |
| Access Control System Panel (8-door) | Main access controller for hotel and spa entry points | 1 | $3,000.00 | $3,000.00 | 6 | $750.00 | $3,750.00 |
| RFID Card Readers | Keycard readers at entrances, spa, and elevator | 6 | $300.00 | $1,800.00 | 2 | $1,500.00 | $3,300.00 |
| Electronic Door Locks | Maglocks/strikes on entry and restricted doors | 6 | $500.00 | $3,000.00 | 3 | $2,250.00 | $5,250.00 |
| Elevator Access Control Interface | Enables keycard floor selection in elevator | 1 | $1,500.00 | $1,500.00 | 4 | $500.00 | $2,000.00 |
| Visitor Management Kiosk | Self-service visitor/vendor sign-in at lobby | 1 | $2,000.00 | $2,000.00 | 2 | $250.00 | $2,250.00 |
| IP Surveillance Cameras (1080p) | Security cameras covering hotel & spa (30+ day recording via NVR) | 24 | $400.00 | $9,600.00 | 2 | $6,000.00 | $15,600.00 |
| Network Video Recorder (NVR) + Storage | Records all camera feeds; 30+ days on storage | 1 | $10,000.00 | $10,000.00 | 16 | $2,000.00 | $12,000.00 |
| Gigabit PoE+ Network Switches (24-port) | Connects & powers IP devices in hotel and spa buildings | 2 | $800.00 | $1,600.00 | 2 | $500.00 | $2,100.00 |
| Equipment Racks & Patch Panels | Main 42U rack (hotel) and secondary cabinet (spa) for equipment | 2 | $750.00 | $1,500.00 | 3 | $750.00 | $2,250.00 |
| UPS Backup Units | Battery backup for main and remote network racks | 2 | $1,000.00 | $2,000.00 | 2 | $500.00 | $2,500.00 |
| **Totals** |  |  |  | **$68,800.00** |  | **$32,500.00** | **$101,300.00** |

### Renovation Proposal  
| Component (Model) | Purpose | Qty | Unit Price | Hardware Subtotal | Labor (hrs each) | Labor Cost (@$125/hr) | Line Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| Smart Thermostat Zone Controllers | Retrofit network thermostats replacing existing HVAC controls | 8 | $250.00 | $2,000.00 | 2 | $2,000.00 | $4,000.00 |
| BMS Server & Software | Central management platform (HVAC, lighting, security) with remote access | 1 | $10,000.00 | $10,000.00 | 32 | $4,000.00 | $14,000.00 |
| Wireless Occupancy Sensors | Occupancy detection in key areas (no wiring retrofit) | 40 | $100.00 | $4,000.00 | 0.5 | $2,500.00 | $6,500.00 |
| Wireless Daylight Sensors | Daylight sensors for lighting adjustment (wireless retrofit) | 10 | $150.00 | $1,500.00 | 0.5 | $625.00 | $2,125.00 |
| Wireless Lighting Control Modules | Relay modules for existing lighting circuits (wirelessly controlled) | 10 | $200.00 | $2,000.00 | 1 | $1,250.00 | $3,250.00 |
| Lighting Control Hub(s) | Wireless lighting system coordinator (links sensors and relays to BMS) | 2 | $600.00 | $1,200.00 | 2 | $500.00 | $1,700.00 |
| Access Control Panel (8-door) | Main controller for new card access system (hotel & spa) | 1 | $3,000.00 | $3,000.00 | 8 | $1,000.00 | $4,000.00 |
| RFID Card Readers | Retrofit card readers at entrances and spa access points | 6 | $300.00 | $1,800.00 | 3 | $2,250.00 | $4,050.00 |
| Electronic Door Locks | Install/upgrade door locks for access control (entry, spa, etc.) | 6 | $500.00 | $3,000.00 | 4 | $3,000.00 | $6,000.00 |
| Elevator Access Integration Kit | Retrofit elevator for keycard floor access | 1 | $1,500.00 | $1,500.00 | 6 | $750.00 | $2,250.00 |
| Visitor Management Kiosk | Visitor sign-in tablet for deliveries/vendors | 1 | $2,000.00 | $2,000.00 | 2 | $250.00 | $2,250.00 |
| IP Surveillance Cameras (1080p) | IP cameras replacing/upgrading existing CCTV (30+ day NVR) | 24 | $400.00 | $9,600.00 | 3 | $9,000.00 | $18,600.00 |
| NVR + 30-day Storage | Network video recorder server (30-day retention for all cameras) | 1 | $10,000.00 | $10,000.00 | 16 | $2,000.00 | $12,000.00 |
| PoE+ Network Switches (24-port) | Network switches for cameras and devices (utilize existing wiring closets) | 2 | $800.00 | $1,600.00 | 2 | $500.00 | $2,100.00 |
| Equipment Rack/Cabinet | Main rack/cabinet for new equipment (fits in existing IT room) | 2 | $750.00 | $1,500.00 | 3 | $750.00 | $2,250.00 |
| UPS Backup Units | Battery backup for new equipment (main and spa cabinets) | 2 | $1,000.00 | $2,000.00 | 2 | $500.00 | $2,500.00 |
| **Totals** |  |  |  | **$56,700.00** |  | **$29,875.00** | **$86,575.00** |

## Pacific Healthcare Tower – 12-Story Medical Building (Los Angeles, CA)  
These proposals outline large-scale systems for a 12-story medical facility. The **New Build** scenario incorporates state-of-the-art multi-floor HVAC, occupancy-based lighting, strict access control (for sensitive areas and visitor management), extensive CCTV coverage, and an enterprise BMS. The **Renovation** plan upgrades an existing facility with minimal disruption, deploying wireless sensors and interfacing with legacy systems where possible.

### New Build Proposal  
| Component (Model) | Purpose | Qty | Unit Price | Hardware Subtotal | Labor (hrs each) | Labor Cost (@$125/hr) | Line Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| BACnet/IP Floor Controllers | Per-floor HVAC controllers managing all zone equipment | 12 | $1,500.00 | $18,000.00 | 4 | $6,000.00 | $24,000.00 |
| Zone Thermostats/Sensors | Temperature sensing devices for individual zones | 120 | $200.00 | $24,000.00 | 1 | $15,000.00 | $39,000.00 |
| Central HVAC Plant Controllers | Controls central chillers, boilers; links them to BMS | 2 | $3,000.00 | $6,000.00 | 8 | $2,000.00 | $8,000.00 |
| BMS Server & Software Platform | Enterprise BMS (dashboards, analytics, fault detection, remote control) | 1 | $15,000.00 | $15,000.00 | 40 | $5,000.00 | $20,000.00 |
| Ceiling-Mount Occupancy Sensors | Detects occupancy in offices/rooms for automatic lights off | 80 | $80.00 | $6,400.00 | 1 | $10,000.00 | $16,400.00 |
| Daylight Sensors | Measures daylight in perimeter areas to dim lighting | 24 | $150.00 | $3,600.00 | 1 | $3,000.00 | $6,600.00 |
| Lighting Control Panels | Floor-level lighting controllers integrating sensors and lights | 12 | $750.00 | $9,000.00 | 3 | $4,500.00 | $13,500.00 |
| Access Control System Panel | Main access panel for building entrances and secure areas | 1 | $5,000.00 | $5,000.00 | 8 | $1,000.00 | $6,000.00 |
| Card Readers (RFID) | Badge readers at entrances, restricted doors, and elevators | 12 | $300.00 | $3,600.00 | 2 | $3,000.00 | $6,600.00 |
| Electronic Door Locks | Electric locks for secure doors (pharmacy, labs, etc.) | 12 | $500.00 | $6,000.00 | 3 | $4,500.00 | $10,500.00 |
| Elevator Access Integration Modules | Elevator control interfaces for badge-restricted floor access | 2 | $1,500.00 | $3,000.00 | 4 | $1,000.00 | $4,000.00 |
| Visitor Management Kiosk | Touchscreen visitor sign-in with badge printing at lobby | 1 | $2,000.00 | $2,000.00 | 4 | $500.00 | $2,500.00 |
| IP Surveillance Cameras (1080p, PoE) | High-resolution cameras (indoors/outdoors) with 30+ day storage | 48 | $400.00 | $19,200.00 | 2 | $12,000.00 | $31,200.00 |
| Enterprise NVR + Storage | Server with extensive storage for 30+ days of 48 camera feeds | 1 | $20,000.00 | $20,000.00 | 24 | $3,000.00 | $23,000.00 |
| PoE+ Network Switches (48-port) | PoE switches to connect and power cameras and IoT devices (multiple IDFs) | 3 | $1,500.00 | $4,500.00 | 2 | $750.00 | $5,250.00 |
| Equipment Rack & Patch Panels | 42U equipment rack with patch panels for central equipment room | 1 | $1,500.00 | $1,500.00 | 4 | $500.00 | $2,000.00 |
| Rack-mount UPS Backup (3kVA) | Backup power for critical security and automation equipment | 1 | $1,500.00 | $1,500.00 | 2 | $250.00 | $1,750.00 |
| **Totals** |  |  |  | **$148,300.00** |  | **$69,050.00** | **$217,350.00** |

### Renovation Proposal  
| Component (Model) | Purpose | Qty | Unit Price | Hardware Subtotal | Labor (hrs each) | Labor Cost (@$125/hr) | Line Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| BACnet Smart Thermostats (zone controllers) | Networked thermostats installed in each zone (replacing old controls) | 120 | $250.00 | $30,000.00 | 2 | $30,000.00 | $60,000.00 |
| Central HVAC Plant Interface Controllers | Add-on controllers to interface existing chillers/boilers to new BMS | 2 | $3,000.00 | $6,000.00 | 8 | $2,000.00 | $8,000.00 |
| BMS Server & Software Platform | Central BMS with unified dashboard (new integration of legacy systems) | 1 | $15,000.00 | $15,000.00 | 48 | $6,000.00 | $21,000.00 |
| Wireless Occupancy Sensors | Occupancy sensors (battery) for lighting control in offices/rooms | 80 | $100.00 | $8,000.00 | 0.5 | $5,000.00 | $13,000.00 |
| Wireless Daylight Sensors | Daylight sensors for retrofit lighting control in bright areas | 24 | $150.00 | $3,600.00 | 0.5 | $1,500.00 | $5,100.00 |
| Wireless Lighting Control Modules | Retrofit wireless relay modules for existing lighting circuits | 40 | $200.00 | $8,000.00 | 1 | $5,000.00 | $13,000.00 |
| Lighting Control Hubs/Gateways | Wireless lighting gateways linking sensors to lighting and BMS | 3 | $600.00 | $1,800.00 | 2 | $750.00 | $2,550.00 |
| Access Control System Panel | Enterprise access controller for doors and elevators (retrofit) | 1 | $5,000.00 | $5,000.00 | 10 | $1,250.00 | $6,250.00 |
| Card Readers (RFID) | Badge readers added to entrances and sensitive area doors | 12 | $300.00 | $3,600.00 | 3 | $4,500.00 | $8,100.00 |
| Electronic Door Locks | Installed/updated door locking hardware for access control system | 12 | $500.00 | $6,000.00 | 4 | $6,000.00 | $12,000.00 |
| Elevator Access Integration Modules | Retrofit elevator interfaces for badge-controlled floor access | 2 | $1,500.00 | $3,000.00 | 6 | $1,500.00 | $4,500.00 |
| Visitor Management Kiosk | Electronic visitor sign-in system for lobby (with badge printing) | 1 | $2,000.00 | $2,000.00 | 4 | $500.00 | $2,500.00 |
| IP Surveillance Cameras | IP cameras replacing old CCTV (cover entrances, corridors; 30+ day storage) | 48 | $400.00 | $19,200.00 | 3 | $18,000.00 | $37,200.00 |
| Enterprise NVR + Storage | Central NVR with storage for all new IP cameras (30+ day retention) | 1 | $20,000.00 | $20,000.00 | 24 | $3,000.00 | $23,000.00 |
| PoE+ Network Switches (48-port) | PoE switches dedicated to security/BMS devices (augment existing network) | 3 | $1,500.00 | $4,500.00 | 2 | $750.00 | $5,250.00 |
| Equipment Rack & Patch Panels | Rack and patch panels to accommodate new equipment in existing IT room | 1 | $1,500.00 | $1,500.00 | 4 | $500.00 | $2,000.00 |
| Rack-mount UPS Backup (3kVA) | UPS to provide backup power to new system rack | 1 | $1,500.00 | $1,500.00 | 2 | $250.00 | $1,750.00 |
| **Totals** |  |  |  | **$158,700.00** |  | **$86,250.00** | **$244,950.00** |