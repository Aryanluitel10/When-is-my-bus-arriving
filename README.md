Bus Location Notifier
I just hate to wait at the bus station. Why not add what you have learned in class to solve your problems?

Features
Real-time bus location data.
Area-specific notifications (e.g., gas station).
Nearby landmark information.
Requirements
Python 3.6+
requests and geopy libraries
Installation
python -m venv bus
pip install -r requirements.txt
Usage
Run the script to get real-time bus data for the "Meridian/A&M" route.
Modify latitude/longitude boundaries in is_bus_in_gas_station() to change the area of interest.
Example Output
Bus 101 is in the gas station area!
Bus 101 is near: DQ Grill & Chill, 214
TODO
Add Alexa push notifications.
Integrate Telegram bot for alerts.
