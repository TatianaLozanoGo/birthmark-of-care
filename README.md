# BIRTHMARKS OF CARE
## Protection leaves a trace

### Tagline
A responsive light object where care, protection, and environment become visible through a living membrane.

---

## Abstract
Birthmark of Care is a responsive light object that explores protection through living biomaterials. A SCOBY (Symbiotic Culture of Bacteria and Yeast) membrane acts as a diffuser, recording care through variations in texture and translucency. Translating environmental noise into breathing light, the object uses light as a metaphor for information, filtering what can be seen or obscured while connecting distant environments.

---

## What It Is
This project transforms the way care and protection can be experienced through light. At its core is a SCOBY membrane, a living biomaterial that grows, filters, and records the care it receives.

Each diffuser is unique. Its thickness, translucency, smell, and surface depend on time, attention, and environmental conditions. These variations become birthmarks of care: material traces that tell a story of nurture, protection, and growth.

---

## Concept
The project began as an exploration of biomaterials, specifically SCOBY. The SCOBY protects and nurtures fermentation, becoming a metaphor for protection and emotional filtering.

This work reflects on inherited protection, distance, and mediated perception between environments.

---

## How It Works — Experience
The project consists of two interconnected lamps located in different spaces (Bogotá and Milan).

Environmental sound is translated into breathing light behavior:
- Calm environments → soft breathing light
- Loud environments → dim, rapid pulsing light

Light intensity determines how much can be seen through the SCOBY membrane.

---

## How It Works — Technical
The system uses ESP32 microcontrollers connected through MQTT communication.

### Listening Node
- ESP32-S3 Mini
- PDM Microphone
- Sound normalized into environmental pressure value
- Controls LED output

### Receiving Node
- ESP32-S2 Mini
- Receives signal via MQTT
- Mirrors light behavior using LED array

---

## SCOBY as a Practice of Care
The diffuser is grown rather than manufactured.

Growth depends on:
- Time
- Feeding
- Environmental stability
- Contamination control

Material variations become visible records of care.

---

## Recipe

### Ingredients
- 400 ml water
- 35 g sugar
- 3 black tea bags
- 1 SCOBY disk
- Optional kombucha + vinegar

### Procedure
Prepare sweet tea solution, inoculate SCOBY, allow fermentation, monitor growth, and dry membrane under tension.

---

## Conceptual Alignment
The system does not transmit sound, images, or data; only light.

What travels through the network is a filtered interpretation of environmental tension and calm.

---

## Credits
Designer: Tatiana Lozano Gómez
Location: Milano, Italia
