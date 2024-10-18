# [English Version](#english-version) | [Versión en Español](#versión-en-español)
---

## English Version

# 🚀 PLC Control System for Motor Operation using Siemens S7-1200, HMI, and VFD  


## 📋 Table of Contents


- [English Version | Versión en Español](#english-version--versión-en-español)
  - [English Version](#english-version)
- [🚀 PLC Control System for Motor Operation using Siemens S7-1200, HMI, and VFD](#-plc-control-system-for-motor-operation-using-siemens-s7-1200-hmi-and-vfd)
  - [📋 Table of Contents](#-table-of-contents)
  - [🎥Project Overview](#project-overview)
  - [🌟 Introduction](#-introduction)
  - [⚙️ Project Features](#️-project-features)
  - [🛠 Requirements](#-requirements)
    - [🔧 Manual Mode](#-manual-mode)
    - [⚙️ Automatic Mode](#️-automatic-mode)
    - [🖥️ HMI Interface](#️-hmi-interface)
    - [🚩 Challenges](#-challenges)
  - [Versión en Español](#versión-en-español)
- [🚀 Sistema de Control PLC para la Operación de Motor usando Siemens S7-1200, HMI y VFD](#-sistema-de-control-plc-para-la-operación-de-motor-usando-siemens-s7-1200-hmi-y-vfd)
  - [📋 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🎥 Descripción del Proyecto](#-descripción-del-proyecto)
  - [🌟 Introducción](#-introducción)
  - [⚙️ Características del Proyecto](#️-características-del-proyecto)
  - [🛠 Requisitos](#-requisitos)
    - [🔧 Modo Manual](#-modo-manual)
    - [⚙️ Modo Automático](#️-modo-automático)
    - [🖥️ Interfaz HMI](#️-interfaz-hmi)
    - [🚩 Desafíos](#-desafíos)

---

## 🎥Project Overview



[![Speed Profile Control - Demo](https://img.youtube.com/vi/550VNGQESG8/0.jpg)](https://youtu.be/550VNGQESG8)

Click on the image above to watch the demo on YouTube.

## 🌟 Introduction
This project implements a control system for a motor using a Siemens **S7-1200 PLC**, an **HMI interface**, and a **variable frequency drive (VFD)** to control the speed and rotation of the motor in two different modes: **Manual** and **Automatic**. The project follows the **ISA-101** standard for HMI design, ensuring a clear and navigable user interface.

The program is developed in **LADDER** and highlights the use of both **digital** and **analog outputs**, along with effective variable management for controlling motor speed, direction, and acceleration times. 🚦

## ⚙️ Project Features
- **Manual Mode**: The operator can manually control the motor's speed and rotation direction.
- **Automatic Mode**: The motor follows a predefined piecewise linear speed profile, which consists of acceleration and deceleration ramps. These ramps are adjusted according to the acceleration time and the desired time values entered by the user. After each cycle, the motor reverses its direction and the sequence starts again.
- **HMI Interface**: A fully navigable HMI interface allows the operator to monitor and control system parameters such as speed, time, and process status.
- **ISA-101 Compliance**: The HMI interface is designed according to ISA-101 standards, ensuring efficient navigation and clarity.
- **Real-Time Monitoring**: The operator can see the motor speed profile, elapsed time, system states, and the current mode of operation.

## 🛠 Requirements
- Siemens **S7-1200 PLC** with TIA Portal.
- **HMI** Panel.
- **Variable Frequency Drive (VFD)**.
- **Motor**.
-  **LADDER programming**.
  

---

### 🔧 Manual Mode
In **Manual Mode**, the operator has control over:
- **Motor Direction**: 🌀 Clockwise or Counterclockwise.
- **Speed**: RPM can be adjusted via the **HMI** interface.
  
The **HMI** window dedicated to manual mode shows the current speed, motor status, and allows input for direction and RPM.

### ⚙️ Automatic Mode
In **Automatic Mode**, the operator can set:
- **Desired Speed** (RPM).
- **Acceleration Time** (minutes).
- **Desired time** (decades of seconds).

The motor follows a **piecewise function**, reversing its direction after each completed sequence. The HMI interface shows real-time data of the motor's speed profile, system state, and elapsed time. ⏲️

---

### 🖥️ HMI Interface
The **HMI** is fully navigable and includes:
- **Manual Mode Window**: Speed, direction, and status.
- **Automatic Mode Window**: Speed profile, time settings, and real-time system monitoring.
- **Status Indicators**: Operating mode, acceleration/deceleration, elapsed time.
  
The HMI is designed with **ISA-101 standards**, ensuring a consistent and intuitive user experience. 📊

---

### 🚩 Challenges
- **Variable Management in LADDER**: The main challenge lies in managing and manipulating variables efficiently in the **LADDER programming** language, handling a variety of data types and performing necessary conversions, as well as managing both analog and digital outputs..
- **ISA-101 Compliance**: Ensuring that the **HMI** is user-friendly while adhering to the ISA-101 standard for industrial interfaces.

---

## Versión en Español

# 🚀 Sistema de Control PLC para la Operación de Motor usando Siemens S7-1200, HMI y VFD  

## 📋 Tabla de Contenidos

- [English Version | Versión en Español](#english-version--versión-en-español)
  - [English Version](#english-version)
- [🚀 PLC Control System for Motor Operation using Siemens S7-1200, HMI, and VFD](#-plc-control-system-for-motor-operation-using-siemens-s7-1200-hmi-and-vfd)
  - [📋 Table of Contents](#-table-of-contents)
  - [🎥Project Overview](#project-overview)
  - [🌟 Introduction](#-introduction)
  - [⚙️ Project Features](#️-project-features)
  - [🛠 Requirements](#-requirements)
    - [🔧 Manual Mode](#-manual-mode)
    - [⚙️ Automatic Mode](#️-automatic-mode)
    - [🖥️ HMI Interface](#️-hmi-interface)
    - [🚩 Challenges](#-challenges)
  - [Versión en Español](#versión-en-español)
- [🚀 Sistema de Control PLC para la Operación de Motor usando Siemens S7-1200, HMI y VFD](#-sistema-de-control-plc-para-la-operación-de-motor-usando-siemens-s7-1200-hmi-y-vfd)
  - [📋 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🎥 Descripción del Proyecto](#-descripción-del-proyecto)
  - [🌟 Introducción](#-introducción)
  - [⚙️ Características del Proyecto](#️-características-del-proyecto)
  - [🛠 Requisitos](#-requisitos)
    - [🔧 Modo Manual](#-modo-manual)
    - [⚙️ Modo Automático](#️-modo-automático)
    - [🖥️ Interfaz HMI](#️-interfaz-hmi)
    - [🚩 Desafíos](#-desafíos)

---

## 🎥 Descripción del Proyecto

[![Control de Perfil de Velocidad - Demo](https://img.youtube.com/vi/550VNGQESG8/0.jpg)](https://youtu.be/550VNGQESG8)

Haz clic en la imagen de arriba para ver el demo en YouTube.

## 🌟 Introducción
Este proyecto implementa un sistema de control para un motor usando un **PLC Siemens S7-1200**, una **interfaz HMI**, y un **variador de frecuencia (VFD)** para controlar la velocidad y la rotación del motor en dos modos diferentes: **Manual** y **Automático**. El proyecto sigue el estándar **ISA-101** para el diseño de la HMI, garantizando una interfaz de usuario clara y navegable.

El programa está desarrollado en **LADDER**, y destaca el uso tanto de **salidas digitales** como **analógicas**, junto con una gestión eficiente de variables para controlar la velocidad del motor, su dirección y los tiempos de aceleración. 🚦

## ⚙️ Características del Proyecto
- **Modo Manual**: El operador puede controlar manualmente la velocidad y la dirección de rotación del motor.
- **Modo Automático**: El motor sigue un perfil de velocidad lineal por tramos, que consiste en rampas de aceleración y desaceleración. Estas rampas se ajustan según los valores deseados ingresados por el usuario. Después de cada ciclo, el motor invierte su dirección y la secuencia comienza de nuevo.
- **Interfaz HMI**: Una interfaz HMI completamente navegable permite al operador monitorear y controlar parámetros del sistema como velocidad, tiempo y estado del proceso.
- **Cumplimiento de ISA-101**: La interfaz HMI está diseñada de acuerdo con los estándares ISA-101, garantizando una navegación eficiente y clara.
- **Monitoreo en Tiempo Real**: El operador puede ver el perfil de velocidad del motor, el tiempo transcurrido, los estados del sistema y el modo de operación actual.

## 🛠 Requisitos
- PLC **Siemens S7-1200** con TIA Portal.
- Panel **HMI**.
- **Variador de Frecuencia (VFD)**.
- **Motor**.
- Programación en **LADDER**.
  

---

### 🔧 Modo Manual
En el **Modo Manual**, el operador tiene control sobre:
- **Dirección del Motor**: 🌀 Sentido horario o antihorario.
- **Velocidad**: Las RPM se pueden ajustar a través de la interfaz **HMI**.
  
La ventana de **HMI** dedicada al modo manual muestra la velocidad actual, el estado del motor y permite la entrada para la dirección y las RPM.

### ⚙️ Modo Automático
En el **Modo Automático**, el operador puede ajustar:
- **Velocidad Deseada** (RPM).
- **Tiempo de Aceleración** (minutos).
- **Tiempo deseado** (décadas de segundos).

El motor sigue una **función por tramos**, invirtiendo su dirección después de cada secuencia completada. La interfaz HMI muestra datos en tiempo real del perfil de velocidad del motor, estado del sistema y tiempo transcurrido. ⏲️

---

### 🖥️ Interfaz HMI
La **HMI** es completamente navegable e incluye:
- **Ventana del Modo Manual**: Velocidad, dirección y estado.
- **Ventana del Modo Automático**: Perfil de velocidad, configuración de tiempos y monitoreo en tiempo real del sistema.
- **Indicadores de Estado**: Modo de operación, aceleración/desaceleración, tiempo transcurrido.
  
La HMI está diseñada según los **estándares ISA-101**, asegurando una experiencia de usuario consistente e intuitiva. 📊

---

### 🚩 Desafíos
- **Gestión de Variables en LADDER**: El principal desafío radica en gestionar y manipular variables de manera eficiente en el lenguaje de programación **LADDER**, manejando una variedad de tipos de datos y realizando las conversiones necesarias, así como gestionando tanto salidas analógicas como digitales.
- **Cumplimiento de ISA-101**: Asegurar que la **HMI** sea fácil de usar mientras se adhiere al estándar ISA-101 para interfaces industriales.
