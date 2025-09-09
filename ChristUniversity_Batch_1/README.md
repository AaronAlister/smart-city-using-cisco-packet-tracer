Aim:
To design and implement a Smart City monitoring system in Cisco Packet Tracer that
integrates smart surveillance, intelligent street lighting, and fire monitoring using IoT devices
to improve safety, efficiency, and automation in urban environments.

Problem Statement:
Design and build an intelligent urban environment for city monitoring, incorporating smart
surveillance, intelligent street lighting and fire monitoring within Cisco Packet Tracer.

Scope of the Solution:
The solution is scalable and can be extended for:
➢ City-wide monitoring of streets, traffic, and homes.
➢ Integration with cloud-based dashboards for real-time analytics.
➢ Reducing human intervention and improving response time to emergencies.
➢ Energy saving through smart lighting automation.
➢ Enhanced safety with automated surveillance and fire safety systems.

Required Components:
Software: 1. Cisco Packet Tracer (IoT Simulation Platform)
Hardware(in CPT): 1. Home Gateway (IoT device controller)
                  2. Motion Detector (for surveillance)
                  3. Webcam (for surveillance monitoring)
                  4. Streetlight (for smart lighting)
                  5. Smoke Detector (for fire detection)
                  6. Fire Sprinkler (for fire suppression)

Theory:
The concept of Smart Cities integrates IoT devices with networking infrastructure to provide
automation, monitoring, and control. In this project:
❖ Surveillance System: A motion detector senses movement and activates a webcam
for recording.
❖ Street Lighting System: Streetlights automatically turn on/off based on external
triggers (time or motion).
❖ Fire Monitoring System: Smoke detectors sense fire/smoke and activate sprinklers
for fire control.
Cisco Packet Tracer provides an environment where IoT devices are connected to a Home
Gateway, enabling rule-based automation using conditions like if-then logic.

Methodology:
1. Open Cisco Packet Tracer.
2. Add Home Gateway as the central IoT controller.
3. From End Devices > Home, drag and place:
● Motion Detector & Webcam (Surveillance).
● Streetlight (Smart lighting).
● Smoke Detector & Fire Sprinkler (Fire monitoring).
4. Connect all devices to the Home Gateway.
5. Configure IoT rules:
★ If Motion Detector = TRUE → Turn ON Webcam.
★ If Night-time/trigger = TRUE → Turn ON Streetlight.
★ If Smoke Detector = TRUE → Activate Fire Sprinkler.
6. Test the system by triggering each sensor.
7. Steps to Do It (Procedure)
  1. Surveillance Setup:
     Place a Motion Detector and Webcam.
     Configure automation: When motion detected → Webcam ON.
  2. Street Lighting Setup:
     Place Streetlight.
     Configure automation: When dark (or triggered) → Streetlight ON.
  3. Fire Monitoring Setup:
     Place Smoke Detector and Fire Sprinkler.
     Configure automation: When smoke detected → Sprinkler ON.
  4. Testing:
     Simulate motion → Webcam activates.
     Simulate night/dark → Streetlight activates.
     Simulate fire → Smoke detector triggers sprinkler

8. Output
The simulation demonstrates:
● Automatic camera activation on motion detection.
● Automatic streetlight operation based on environment.
● Automatic fire response using smoke detector and sprinkler.
This shows a functional smart city model with integrated IoT-based monitoring and control.
