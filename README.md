Arduinobot – ROS 2 Workspace
Projekt robota mobilnego oparty o ROS 2.
Workspace zawiera konfigurację URDF, pliki launch oraz konfigurację RViz.

Aktualny stan
[x] Struktura ROS 2 workspace
[x] Model robota (URDF)
[x] Konfiguracja RViz
[ ] Integracja z Arduino (ros2_control / serial)
[ ] Sterowanie i sensory

Technologie
ROS 2 (Humble)
C++ / Python
RViz2
URDF / TF

Uruchomienie
```bash
colcon build
source install/setup.bash