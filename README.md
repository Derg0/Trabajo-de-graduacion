# Diseño de Sistema de Comunicación por Voz en Redes Inalámbricas WiFi

Este repositorio contiene los **esquemáticos y  layout** del circuito impreso (PCB) desarrollado para el trabajo de graduación titulado:

> **“Diseño de Sistema de Comunicación por Voz en Redes Inalámbricas WiFi”**  
---

## 📘 Descripción General

El proyecto desarrolla un **sistema de comunicación por voz (PTT)** sobre una red local WiFi.  
El sistema utiliza una **Orange Pi Zero 2W** con **Debian Linux** y software de comunicación **Mumble**, junto a un **módulo de alimentación autónomo** diseñado especialmente para garantizar operación estable y portable mediante baterías de iones de litio.

El **PCB de alimentación** se diseñó para ser **mecánicamente compatible** con la Orange Pi Zero 2W, proporcionando **5V regulados** y permitiendo **carga  y operación continua** del dispositivo.

---

## ⚙️ Características del PCB

- **Dimensiones:** 30 mm x 65 mm x 1.2 mm  
- **Controlador de carga:** MCP73213 (baterías Li-ion)  
- **Regulador buck:** MP2338 (salida 5V / hasta 3A)  
- **Baterías:** 2× 18650 en serie (7.4V nominales)  
- **Puertos:**
  - Micro-USB (entrada de carga)
  - USB tipo A (salida de alimentación a Orange Pi)
- **Compatibilidad mecánica:** Orange Pi Zero 2W  
- **Montaje:** 4 agujeros de 3 mm (alineados con los de la Orange Pi)

---

## 🧩 Archivos Incluidos

- `/Schematics/` → Archivos esquemáticos del circuito (MCP73213 y MP2338)  
- `/PCB_Layout/` → Archivos de diseño del PCB (formato Gerber, Drill, etc.)  
