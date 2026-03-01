KAZZAR prototype is a lightweight single-propeller RC drone prototype designed and assembled using off-the-shelf electronic components. The project focuses on understanding propulsion systems, power distribution, flight stability, and real-time FPV (First Person View) transmission.Project Objectives

Design and assemble a functional single-motor drone system

Implement stable thrust and control mechanisms:

Integrate an FPV video transmission system

Capture aerial footage using an onboard action camera

Document the system architecture professionally

System Architecture:

The drone operates using a brushless DC motor powered by a 3S LiPo battery. Motor speed is regulated through an Electronic Speed Controller (ESC), which receives throttle signals from the RC receiver.

The FPV system operates independently, transmitting live analog video from the onboard FPV camera via a 5.8GHz transmitter to a mobile receiver device.

The action camera is used for high-resolution video recording, separate from the live FPV feed.

Below is the full 3D render of the drone assembly:
<p align="center">
  <img src="Quadcopter Image.jpg" width="600">
</p>

The system wiring is based on direct component integration (no custom PCB used).

Power Flow:

LiPo Battery → ESC

ESC → Brushless Motor

Control Signal Flow:

RC Receiver → ESC (Throttle Signal)

RC Receiver → Servos (Control Surfaces)

FPV System:

LiPo Battery → Voltage Regulator

Regulator → FPV Camera

Camera → 5.8GHz Video Transmitter

Transmitter → Mobile Receiver (via OTG)

<p align="center">
  <img src="flow chart.png" width="600">
</p>

Key Components

Brushless Motor

Electronic Speed Controller (ESC)

3S 2200mAh LiPo Battery

RC Transmitter & Receiver

Servo Motors

FPV Camera (600–700TVL)

5.8GHz Video Transmitter

Android OTG 5.8GHz Receiver

4K Action Camera

Technical Focus Areas:

Power-to-weight optimization

Voltage regulation for auxiliary systems

Vibration isolation for video stability

Proper signal routing and interference reduction

Safe LiPo battery handling

Future Improvements

Custom Power Distribution PCB

Flight controller integration

Telemetry system

Improved aerodynamic frame design

Digital FPV upgrade

| Component | Specification | Quantity | Link |
|-----------|--------------|----------|------|
| Brushless Motor | 2200KV | 4 | https://robu.in/product/2212-920kv-brushless-motor-dji-red/ |
| ESC | 40A | 1 | https://robu.in/product/40a-2-6s-esc-3-5mm-banana-connector/ |
| LiPo Battery | 11.1V 2200mAh 3S | 1 | https://robu.in/product/orange-2200mah-3s-30c60c-lithium-polymer-battery-pack-lipo/ |
| Propeller | 10x4.5 | 4 | https://robu.in/product/orange-hd-propellers-104510x4-5-abs-1cw1ccw-1pair-black/ |
| FPV Camera | 600–700TVL | 1 | https://www.electropi.in/1-3-cmos-1500tvl-mini-fpv-camera-21mm-lens-pal-ntsc-with-osd |
| Video Transmitter | 5.8GHz | 1 | https://www.electropi.in/ts835-fpv-58g-600mw-48ch-2-6s-wireless-av-transmitter |
| Phone Receiver | 5.8GHz UVC OTG | 1 | https://www.electropi.in/58g-uvc-otg-android-av-phone-receiver |
| Action Camera | 4K 30fps | 1 | https://www.amazon.in/gp/product/B0G1ZFP9KL/ref=ox_sc_act_title_1?smid=A2HRG2XMGIR8NW&psc=1 |
| Quadcopter Frame |F450 / Q450 with Integrated PCB| 1 | https://robu.in/product/q450-quadcopter-frame-with-arm-with-integrated-pcb/ |
| Flight Controller |Supports SBUS and PPM receivers| 1 | https://robu.in/product/radiolink-byme-a-flight-controller/ | 
| Compact Balance Charger|IMAX B3 AC Pro | 1 | https://robu.in/product/b3ac-compact-balance-charger-2s-3s-lipo/ | 
| Male Connector|XT60-M.G.Y | 1 | https://robu.in/product/amass-xt60-male-connector-xt60-m-g-y/ | 
| Heat Shrink Tube|328PCS Retardant 2:1| 1 pack | https://robu.in/product/328pcs-heat-shrink-tube-heat-shrink-tube-kit/ | 
| Nylon Cable Zip |100mm white| 1 pack| https://robu.in/product/nylon-cable-zip-ties-100mm-100pcs-bag-1-bag/ | 
| Stmicroelectronics-Buck |ST1S12G12R| 1 | https://robu.in/product/st1s12g12r-stmicroelectronics-buck-step-down-switching-regulator-fixed-2-5v-to-5-5v-in-1-2v-700ma-out-1-7mhz-tsot235/ | 
| Male Female Wire Bullet Connector|3.5mm | 1 | https://makerbazar.in/products/male-female-wire-bullet-connector-3-5mm?variant=20308177780832 | 
|transmitter and receiver| CT6B 2.4GHz 6CH Transmitter with FS-R6B Receiver | 1 | https://makerbazar.in/products/flysky-ct6b-2-4ghz-6ch-transmitter-with-fs-r6b-receiver?variant=38389721006231 | 
|Screws |M3 Shock Absorber Screws| 1pack |https://www.electropi.in/m3-shock-absorber-screws-4-pieces-pack?search=shock%20absorber%20screws |





























