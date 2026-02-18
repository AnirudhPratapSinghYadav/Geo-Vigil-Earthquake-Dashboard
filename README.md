🌍 Geo-Vigil: Agentic Earthquake Dashboard
Official Project Demo for Gemini Summer of Code 2026

📖 Overview
Geo-Vigil is an immersive seismic visualization tool built for the Liquid Galaxy. It transforms live earthquake data from the USGS API into a 3D experience. This app was developed using the Agentic Programming workflow: taking the LG-Starter-Kit and using Google Antigravity + Gemini to automate the complex KML logic.

✨ Key Features
🌋 Live USGS Integration: Fetches real-time seismic data globally.

🗼 3D Hazard Pillars: Earthquake magnitude is visualized as 3D red towers on the Master rig using <extrude> tags.

🔄 Cinematic 360° Orbit: A smooth, automated camera sweep around the epicenter to view disaster topography.

📊 Multi-Screen HUD:

Left Screen (Slave 3): Project branding and Liquid Galaxy logo.

Right Screen (Slave 2): Tactical HUD with location details, depth, and magnitude.

🗺️ Tectonic Overlay: Visualizes plate boundaries to provide geological context.

🤖 Built with Intelligence
This app is the result of working with the .agent/skills system. By providing the AI with the KML Mastery Skill and Rig Orchestration Skill, the agent generated the following:

Automatic 65° Tilt: Perfect for viewing 3D pillars.

Dynamic Scaling: The height of the pillars is calculated automatically based on magnitude.

Sequential Resource Loading: Ensuring the AI voice and video play perfectly without lag.

🚀 Installation & Setup
Clone the Repo:

Bash
git clone https://github.com/AnirudhPratapSinghYadav/geo-vigil-app.git
Install Dependencies:

Bash
flutter pub get
Run the App:

Bash
flutter run --no-enable-impeller
Connect: Enter your Liquid Galaxy IP and credentials on the Connection Page.

🎥 Video Demonstration
Watch the Full Project Walkthrough on youtube(coming soon...)
Includes: Repository walkthrough, Agent skills explanation, and live demo.

📜 License
Distributed under the MIT License. See LICENSE for more information.
