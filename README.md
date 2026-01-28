 homeassistant-navigation-dashboard

A clean and modular navigation dashboard template for Home Assistant.
Designed as a central hub for dashboards, media, add-ons and web shortcuts.
This template is ideal for wall-mounted tablets, car-mounted tablets, or users who want a structured navigation menu inside Home Assistant.

🚀 Features
• 	Four organized views:

• 	Dashboards

• 	Media

• 	Add-ons

• 	Web

• 	Example button in each view showing how to build your own cards

• 	Uses  for clean and modern UI

• 	Easy to expand with your own links, dashboards, apps or services

• 	Fully English and universal — no personal URLs included

📥 How to Install
1. Download the dashboard file
Download the file:
https://raw.githubusercontent.com/hanspettervalle-prog/homeassistant-navigation-dashboard/main/dashboard.yaml

(You can right-click → Save As)
2. Import into Home Assistant
1. 	Go to Settings → Dashboards
2. 	Click + Add Dashboard
3. 	Give it a name (e.g., “Navigation”)
4. 	Open the dashboard
5. 	Click ⋮ → Edit Dashboard
6. 	Click Raw configuration editor
7. 	Delete everything inside
8. 	Paste the content of `dashboard.yaml` 
9. 	Save

Your navigation dashboard is now ready.

🧭 How to Add Your Own Buttons
Each view contains one example card.
To add more:
1. 	Click Edit Dashboard
2. 	Click Add Card
3. 	Choose Manual
4. 	Paste a modified version of the example card
Example: Add a dashboard shortcut

Example: Add a website

Example: Add an add-on


🎨 Styling
All example cards include:
• 	background color
• 	rounded corners
• 	centered icon and text
• 	consistent height
You can freely change colors, icons and layout.

📂 File Structure

(You can add an  folder later if you want.)

📄 Requirements
• 	Home Assistant
• 	 installed via HACS
(HACS → Frontend → Search for “button-card”)

🧩 License
You may add a license here if you want (MIT is common for templates).
