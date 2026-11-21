<h1 align="center">Yıldıray Sabancı</h1>
<p align="center">Game developer · Embedded systems developer · Ankara, Türkiye</p>

I build the software that sits between an aircraft and the people flying it:
flight-controller firmware, simulators, ground stations and the tooling around
them. Most of that work happens in **NeuroFlight**, an end-to-end UAV
development stack I am building.

## Now: NeuroFlight

- **Simulator** · Unreal Engine 5 (source build) with MAVLink in the loop, so
  the same autopilot code flies in the simulator and on the bench.
- **Flight control** · flight-controller firmware, with PX4, INAV and ArduPilot
  as reference points.
- **Ground station** · [MavGCS](https://github.com/yildiraysabanci/MavGCS), a
  MAVLink ground-control station in Python.
- **Analysis** · aircraft physics, CFD and design tooling (OpenFOAM, XFLR5,
  OpenVSP) feeding the simulator.
- **Learning** · Gym-style environments around the simulator for
  reinforcement-learning experiments.
- **Platform** · real-time Linux and Yocto images for the onboard computers.

The core repositories stay private while the project is in development; the
public pieces are listed below.

## Also interested in

RISC-V and digital design (CVA6, OpenTitan, the Caravel/OpenLane flow), game
development in Unreal and Unity, and a terminal-centric Linux workflow
(Neovim, tmux, fish on CachyOS).

## Stack

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-1E88E5?style=flat-square&logo=px4&logoColor=white)
![ArduPilot](https://img.shields.io/badge/ArduPilot-E3242B?style=flat-square)
![INAV](https://img.shields.io/badge/INAV-2E7D32?style=flat-square)
![MAVLink](https://img.shields.io/badge/MAVLink-455A64?style=flat-square)
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Yocto](https://img.shields.io/badge/Yocto-5A97D5?style=flat-square&logo=yoctoproject&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1A5276?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)

## Public repositories worth a look

| Repository | What it is |
|---|---|
| [MavGCS](https://github.com/yildiraysabanci/MavGCS) | Ground-control station for MAVLink vehicles, written in Python. |
| [Cpp-Libraries](https://github.com/yildiraysabanci/Cpp-Libraries) | A curated map of C/C++ libraries for embedded systems, robotics, UAVs and real-time work. |
| [VR-FlightSimulatorSilantro](https://github.com/yildiraysabanci/VR-FlightSimulatorSilantro) | VR flight-simulator prototype in Unity. |
| [lora_stm32_communication](https://github.com/yildiraysabanci/lora_stm32_communication) | LoRa radio link on an STM32 microcontroller. |
| [SerialMonitor](https://github.com/yildiraysabanci/SerialMonitor) | A serial monitor that runs in the browser, one HTML file. |

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yildiraysabanci/yildiraysabanci/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yildiraysabanci/yildiraysabanci/output/github-snake.svg">
  <img alt="Contribution graph drawn as a snake, regenerated nightly" src="https://raw.githubusercontent.com/yildiraysabanci/yildiraysabanci/output/github-snake.svg">
</picture>

<sub>The snake is redrawn every night by a GitHub Action in this repository; the rest of the page is written by hand.</sub>
