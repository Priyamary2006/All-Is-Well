<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# All Is Well 🎯

## Basic Details

### Team Name: Priya Mary Abraham

### Team Members
- Member 1: Priya Mary Abraham - Mar Baselios Christian College of Engineering and Technology

### Hosted Project Link
[mention your project hosted link here]

### Project Description
An AI-driven Smart City & Safety Hub that integrates real-time IoT tracking for household essentials with a live mapping system for urban utilities. It features hands-free SOS voice triggers and automated safety checklists to bridge the gap between personal security and public infrastructure management.

### The Problem statement
Existing urban solutions often operate in silos, forcing users to switch between multiple apps for home security, personal safety, and public utility information. This fragmentation leads to delayed emergency responses and inefficient management of daily household or city-level tasks.

### The Solution
"All Is Well" provides a unified command center that synchronizes personal safety with public infrastructure data. It automates "leaving-home" rituals with context-aware checklists, monitors city-wide utility levels (like waste bins) via live heat-mapping, and provides an "always-on" safety net using the Web Speech API for hands-free emergency SOS triggers.

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML5, CSS3 (Tailwind CSS), JavaScript (ES6+)
- Frameworks used: Tailwind CSS (via CDN)
- Libraries used: Leaflet.js (Mapping), Lucide Icons (Iconography), Web Speech API (Voice Recognition)
- Tools used: VS Code, Git, Browser Developer Tools

**For Hardware:**
- Main components: Smartphone Sensors (Accelerometer, Microphone)
- Specifications: Requires WebKit-based browser for Speech Recognition
- Tools required: Mobile Device with GPS and Internet connectivity

---

## Features


- Dynamic IoT Checklist: Filters household essentials (Keys, ID, Chargers) based on trip type (Work/Walk/Trip) to prevent forgotten items.
- Urban Utility Heat-Map: Real-time visualization of city assets like Dustbins and Toilets with color-coded status (Green: Empty, Red: Full).
- Voice Guard SOS: Hands-free emergency trigger using keyword detection ("Help", "Sahaayikkane") with an automatic 5-second countdown.
- Shadow Escort: A motion-monitoring mode that detects sudden impacts or falls during transit to alert emergency contacts.
- Quick-Access Emergency Hub: Instant dialing for Police and Pharmacy facilities directly from the map interface.

---

## Implementation

### For Software:

#### Installation
```bash
# No installation required for this standalone frontend project.
# Simply clone the repository
git clone https://github.com/your-username/all-is-well.git
```

#### Run
```bash
# Open index.html in any modern web browser
# (Speech recognition requires a secure context or localhost)
```



## Project Documentation

### For Software:

#### Screenshots

[Screenshot1]<img width="1851" height="872" alt="Screenshot 2026-03-02 195909" src="https://github.com/user-attachments/assets/df78eb49-b2d6-4aa2-ab95-8325ff2d8b8c" />
Home Dashboard
*It shows IoT item status and "Verify" functionality.*

[Screenshot2] <img width="1908" height="895" alt="Screenshot 2026-03-02 195944" src="https://github.com/user-attachments/assets/11aaa990-f17a-4dc6-af2e-1d55be255e4a" />
The Urban Utility Map
*It shows color-coded city assets.*

[Screenshot3]<img width="1910" height="888" alt="Screenshot 2026-03-02 200008" src="https://github.com/user-attachments/assets/a43ead7c-79ac-4b4f-a09b-d92b143a67e8" />
The Dashboard for Police Station
*It shows the details of police station*

#### Diagrams

**System Architecture:**

[Architecture Diagram]

<img width="1408" height="768" alt="Gemini_Generated_Image_9ccog49ccog49cco" src="https://github.com/user-attachments/assets/f6644d8b-5821-4f8f-ae8d-2b766357aa29" />
*This diagram shows the relationship between the Frontend UI, the browser APIs (Speech/Location), and the external data layers.*


**Application Workflow:**

[Workflow]
<img width="1408" height="768" alt="Gemini_Generated_Image_lx7w55lx7w55lx7w" src="https://github.com/user-attachments/assets/42a81a0f-63c5-462f-a78f-18e31fe93a55" />
*The All Is Well workflow follows a state-driven logic that begins in the Home View, where a contextual filtering system adjusts safety checklists based on the user's selected trip type. Once verified, the application transitions to the Leaving View, a dual-layer environment that simultaneously renders a real-time Leaflet.js map for urban utility tracking while activating a background Sensor Layer. This layer utilizes the Web Speech API to maintain a continuous monitoring loop, specifically looking for distress keywords or sudden motion impacts. If a threat is detected, the system executes an SOS Intercept, overriding the standard UI with a high-priority emergency countdown and visual alerts, effectively bridging the gap between proactive home preparation and reactive urban safety.*

---



## Additional Documentation
For Scripts/CLI Tools:
Command Reference
Voice Trigger Keywords:

- Help / Emergency (English)
- Sahaayikkane / Ayo (Malayalam)

Map Status Colors:

- Green: Level < 50% (Empty/Available)
- Yellow: Level 50% - 85% (Half-full)
- Red: Level > 85% (Critical/Full)



---

## Project Demo

### Video

https://github.com/user-attachments/assets/267bd3c3-c052-447b-aa66-44849a13db8e


*The project demo video showcases a seamless transition from a smart home environment to an active urban safety mode. It begins by demonstrating the Home Dashboard, where the user interacts with the Context-Aware Safety Checklist to verify essentials like keys and chargers, which dynamically filter based on the intended trip type. The flow then moves into the City View, featuring the Live Urban Utility Map where Leaflet-powered markers change color (Green to Red) in real-time to reflect the status of public facilities. A critical highlight of the video is the Voice Guard SOS, demonstrating how the Web Speech API processes keywords like "Sahaayikkane" to trigger a 5-second emergency countdown and screen-flash animation. Finally, the video captures the Shadow Escort logic, simulating an impact detection that instantly notifies authorities, proving how the system functions as a proactive protective companion throughout the user's journey.*

---

## AI Tools Used 


**Tool Used:** Gemini

**Purpose:**
- Generating boilerplate JavaScript for Leaflet.js integration.
- Logic optimization for the Voice SOS countdown timer.

**Key Prompts Used:**
- Implement a Leaflet.js map that changes marker colors dynamically based on a 'fill-level' percentage (Green, Yellow, Red).
- Develop a hands-free SOS trigger using the Web Speech API that listens for specific keywords like 'Help' or 'Sahaayikkane'.

**Percentage of AI-generated code:** 30%

**Human Contributions:**
- Project concept and UX workflow design.
- Custom CSS/Tailwind styling for the Glassmorphic UI.
- Integration of specific Indian-context emergency features.


---

## Team Contributions

- Priya Mary Abraham: End-to-end development, UI Design, Mapping integration, and Documentation.
  
---

## License

This project is licensed under the MIT License.

---

Made with ❤️ at TinkerHub
